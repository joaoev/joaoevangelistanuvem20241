# Atividade 03

## Módulo 2 - Economia e faturamento da nuvem

## Questão 01 - 0,5 Pontos

Resolva o Teste de Conhecimento do **Módulo 2 - Economia e faturamento da nuvem**. Se você tirar 80 pontos no Teste de Conhecimento, receberá 0,8 * 0,5 = 0,4 pontos nesta questão.

## Questão 02 - 0,5 Pontos

Como arquiteto de nuvem, você precisa fazer uma estimativa para uma empresa que deseja começar a migração para a nuvem. Atualmente, no datacenter on premises, eles possuem um conjunto de máquinas que totalizam 64 cores e 128 GB de RAM, executando um sistema Linux sem custo de licença, cada uma com disco de 256GB para suportar a instalação do sistema operacional com todas as dependências. Segundo o projetista da aplicação, qualquer quantidade de máquinas virtuais será suficiente, desde que no total somem a mesma ou maior quantidade de cores e memória RAM, mas o mesmo disco de 256 GB por instância. O gerente financeiro afirma que não vê problema em fazer pagamentos adiantados, desde que o custo mensal seria reduzido. Já o gerente de relacionamentos exige que a aplicação seja hospedada no Brasil, pois é uma exigência de alguns clientes.

Além dos servidores de aplicação, os desenvolvedores precisam de um banco de dados Oracle para uma base da dados de 512 GB, porém ainda não possuem a licença. A carga não é tão grande, portanto uma instância de 2 cores e no mínimo 4GB é suficiente, mas eles não desejam se responsabilizar pela configuração do sistema operacional da instância, e nem dos detalhes de configuração e atualizações de segurança do servidor de banco de dados.

Seu papel nesta atividade é fazer uma estimativa para o cenário acima usando a Calculadora de preços da AWS. Você deve pesquisar na documentação da AWS quais os serviços de criação de máquinas virtuais e de fornecimento de bancos de dados Oracle gerenciados e informar os requisitos do cenário. Qualquer campo da estimativa que não mencionado na descrição deve ser configurado para uma opção que reduza o custo mensal da estimativa.

Resposta:

Segundo o projetista da aplicação, qualquer quantidade de máquinas virtuais será suficiente, desde que no total somem a mesma ou maior quantidade de cores e memória RAM, para isso dividi total de cores 64/4 e total de memória 128/8, o que da 16 máquinas com 4 cores e 8GB cada e usando o sistema operacional Linux. Instância escolhida: c6g.xlarge | Family: c6g | 4vCPU | 8 GB Memória

Para o armazenamento coloquei o mesmo total da exigência que era pedida, 256GB SSD de uso geral (gp2).

 Como o gerente financeiro afirma que não vê problema em fazer pagamentos adiantados, desde que o custo mensal seria reduzido, selecionei na opção de pagamento o plano Compute Savings Plans que  tem o prazo da reserva de 3 anos e pagamento adiantado integral, que deu um custo inicial total de 43,225.34 USD e 778.24 USD por mês por conta do armazenamento das instâncias.

Já que o gerente de relacionamentos exige que a aplicação seja hospedada no Brasil, pois é uma exigência de alguns clientes, escolhi a região América do Sul (São Paulo).

Para o banco de dados usei o serviço Amazon RDS for Oracle e como não possuem a licença foi feita a inclusão, a configuração do banco foi feita conforme os requisitos 2 cores, 4GB de memória (db.t2.medium), e 512 GB de armazenamento que ficou com custo mensal de 537,64 USD

Com isso ficou: 
Custo total de 12 meses
59.015,90 USD
Inclui um custo inicial

Aqui está o link da [AWS Pricing Calculator](https://calculator.aws/#/estimate?id=6366089ba1cef164140e64f7593c513c88cc2168)