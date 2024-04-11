# Atividade 04

## Módulo 3 - Visão geral da infraestrutura global da AWS

## Questão 01 - 1,0 Ponto
Resolva o Teste de Conhecimento do **Módulo 3 - Visão geral da infraestrutura global da AWS**. Se você tirar 80 pontos no Teste de Conhecimento, receberá 0,8 * 1 = 0,8 pontos nesta questão.

## Questão 02 - 1,0 Ponto
Responda aos itens a seguir:

1. Quais os fatores que você deve considerar na seleção de uma região da AWS? Comente brevemente sobre cada um deles.
	- **Governança de dados e os requisitos legais**: Cada país tem sua legislação, as leis locais podem exigir que determinadas informações sejam mantidas dentro de limites geográficos. Um exemplo de lei brasileira é a Lei Geral de Proteção de Dados Pessoais.
	- **Proximidade com os clientes (latência)**:  Executar aplicações em uma Região que esteja mais próxima possível do usuário e dos sistemas que os acessarão, isso ajuda a reduzir a latência.
	- **Serviços disponíveis na região**: Nem todos os serviços da estão disponíveis em todas as regiões. 
	- **Custos**: Variam de acordo com a Região.

3. Acesse [Infraestrutura da AWS](https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/) e liste, de todas as regiões disponíveis da AWS, quais tem um número de zonas de disponibilidade maior ou igual a três. Cite o nome da região e a quantidade de zonas.
	**América do Norte**
	Região Oeste dos EUA (Oregon)
	Zonas de disponibilidade: 4
	Lançamento em 2011
	Zonas locais: 7
	Lançamento em 2019
	
	Região Leste dos EUA (Norte da Virgínia)
	Zonas de disponibilidade: 6
	Lançamentos de 2006
	Zonas locais: 10
	Lançamento em 2020
	
	Região Oeste dos EUA (Norte da Califórnia)
	Zonas de disponibilidade: 3*
	Lançamento em 2009
	
	Região Leste dos EUA (Ohio)
	Zonas de disponibilidade: 3
	Lançamento em 2016
	
	Região Canadá (Central)
	Zonas de disponibilidade: 3
	Lançamento em 2016
	
	Região Oeste do Canadá (Calgary)
	Zonas de disponibilidade: 3
	Lançamento em 2023
	
	Região GovCloud (Oeste dos EUA)
	Zonas de disponibilidade: 3
	Lançamento em 2011
	
	Região GovCloud (Leste dos EUA)
	Zonas de disponibilidade: 3
	Lançamento em 2018
	
	**América do Sul**
	Região da América do Sul (São Paulo)
	Zonas de disponibilidade: 3*
	Lançamento em 2011
	
	**Europa**
	Região da Europa (Irlanda)
	Zonas de disponibilidade: 3
	Lançamento em 2007
	
	Região da Europa (Frankfurt)
	Zonas de disponibilidade: 3
	Lançamento em 2014
	
	Região Europa (Londres)
	Zonas de disponibilidade: 3
	Lançado em 2016
	
	Região Europa (Paris)
	Zonas de disponibilidade: 3
	Lançamento em 2017
	
	Região Europa (Estocolmo)
	Zonas de disponibilidade: 3
	Lançamento em 2018
	
	Região da Europa (Milão)
	Zonas de disponibilidade: 3
	Lançamento em 2020
	
	Região Europa (Zurique)
	Zonas de disponibilidade: 3
	Lançamento em 2022
	
	Região Europa (Espanha)
	Zonas de disponibilidade: 3
	Lançamento em 2022
	
	**Oriente Médio**
	Região do Oriente Médio (Bahrein)
	Zonas de disponibilidade: 3
	Lançamento em 2019
	
	Região do Oriente Médio (EAU)
	Zonas de disponibilidade: 3
	Lançamento em 2022
	
	Região de Israel (Tel Aviv)
	Zonas de disponibilidade: 3
	Lançamento em 2023
	
	**África**
	Região da África (Cidade do Cabo)
	Zonas de disponibilidade: 3
	Lançamento em 2020
	
	**Ásia-Pacífico**
	Região da Ásia-Pacífico (Singapura)
	Zonas de disponibilidade: 3
	Lançamento em 2010
	
	Região da Ásia-Pacífico (Tóquio)
	Zonas de disponibilidade: 4
	Lançamento em 2011
	
	Região Ásia-Pacífico (Seul)
	Zonas de disponibilidade: 4
	Lançamento em 2016
	
	Região da Ásia-Pacífico (Mumbai)
	Zonas de disponibilidade: 3
	Lançado em 2016
	
	Região Ásia-Pacífico (Hong Kong)
	Zonas de disponibilidade: 3
	Lançamento em 2019
	
	Região da Ásia-Pacífico (Osaka)
	Zonas de disponibilidade: 3
	Lançamento em 2021
	
	Região da Ásia-Pacífico (Jacarta)
	Zonas de disponibilidade: 3
	Lançamento em 2021
	
	AWS da Região da Ásia-Pacífico (Hyderabad)
	Zonas de disponibilidade: 3
	Lançamento em 2022
	
	Região da China Continental (Pequim)
	Zonas de disponibilidade: 3
	
	Região da China Continental (Ningxia)
	Zonas de disponibilidade: 3
	
	**Austrália**
	Região da Austrália (Sydney)
	Zonas de disponibilidade: 3
	
	Lançamento em 2012
	Região Austrália (Melbourne)
	Zonas de disponibilidade: 3
	Lançado em 2023

## Questão 03 - 1,0 Ponto
Para cada categoria de serviços da AWS abaixo cite e defina três serviços. A definição pode ser curta, uma frase apenas. Também informe um link para a página de documentação oficial do serviço no site de documentação da AWS.

1. Armazenamento
	- **Amazon Simple Storage Service (Amazon S3)**: É um serviço de armazenamento de objetos que oferece dimensionamento, disponibilidade de dados, segurança e desempenho.[Documentação](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)
	
	- **O Amazon Elastic Block Store (Amazon EBS)**: É um serviço de armazenamento em blocos de alto desempenho projetado para uso com o Amazon EC2 para cargas de trabalho com throughput e uso intensivo de transações.[Documentação](https://docs.aws.amazon.com/pt_br/ebs/latest/userguide/what-is-ebs.htmll)
	
	- **O Amazon Elastic File System (Amazon EFS)**: Fornece um sistema de arquivos NFS totalmente gerenciado, dimensionável e elástico para uso com os AWS Cloud Services e recursos on-premises.[Documentação](https://docs.aws.amazon.com/pt_br/efs/latest/ug/whatisefs.html)
	
2. Computação
	- **Amazon Elastic Compute Cloud (Amazon EC2)**: Oferece uma capacidade de computação redimensionável como máquinas virtuais na nuvem.[Documentação](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html)
	
	- **Amazon EC2 Auto Scaling**: Permite que você adicione ou remova automaticamente instâncias do EC2 de acordo com as condições que você definir.[Documentação](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
	
	- **Amazon Elastic Container Service (Amazon ECS)**: É um serviço de orquestração de contêineres altamente escalável e de alto desempenho que oferece suporte a contêineres do Docker.[Documentação](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/Welcome.html)

3. Banco de Dados
	- **Amazon Relational Database Service (Amazon RDS)**: Facilita configurar, operar e escalar um banco de dados relacional na nuvem.[Documentação](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
	
	- **Amazon Aurora**:  É um banco de dados relacional compatível com MySQL e PostgreSQL.[Documentação](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)
	
	- **Amazon DynamoDB**: É um banco de dados de documentos e chave-valor que oferece performance inferior a 10 milissegundos em qualquer escala, com segurança incorporada, backup e restauração e armazenamento em cache na memória.[Documentação](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

4. Rede e Entrega de Conteúdo
	- **Amazon Virtual Private Cloud (Amazon VPC)**: Permite provisionar seções logicamente isoladas da Nuvem AWS.[Documentação](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
	
	- **Elastic Load Balancing**: Distribui automaticamente o tráfego de entrada dos aplicativos entre vários destinos, como instâncias do Amazon EC2, contêineres, endereços IP e funções do Lambda.[Documentação](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)
	
	- **Amazon CloudFront**: É um serviço rápido de rede de entrega de conteúdo (CDN) que entrega dados, vídeos, aplicativos e interfaces de programação de aplicativos (APIs) para clientes em todo o mundo, com baixa latência e altas velocidades de transferência.[Documentação](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)