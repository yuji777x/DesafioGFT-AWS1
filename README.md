Gerenciando Instâncias EC2 na AWS
O que aprendi

Durante este laboratório aprendi como funciona o Amazon EC2 e como ele permite criar e gerenciar servidores virtuais na nuvem de forma prática. Também entendi a importância de escolher corretamente o tipo de instância de acordo com a necessidade da aplicação, levando em consideração processamento, memória e armazenamento.

Outro conceito importante foi a diferença entre escalabilidade vertical e escalabilidade horizontal. Aprendi que a escalabilidade vertical consiste em aumentar ou diminuir os recursos da própria instância, enquanto a escalabilidade horizontal adiciona novas instâncias para dividir a carga de trabalho.

Amazon EC2

O Amazon EC2 (Elastic Compute Cloud) é um serviço da AWS que permite criar máquinas virtuais na nuvem.

Com ele é possível:

Hospedar aplicações;
Criar servidores web;
Criar ambientes de desenvolvimento;
Realizar testes;
Executar aplicações de forma escalável.

Também aprendi que a AWS oferece diversos tipos de instâncias, cada uma voltada para uma necessidade específica, como maior processamento, mais memória ou maior capacidade de armazenamento.

AMI (Amazon Machine Image)

Aprendi que uma AMI funciona como uma imagem completa de uma máquina virtual.

Ela armazena:

Sistema operacional;
Aplicações instaladas;
Configurações;
Dependências e pacotes.

Esse recurso facilita bastante a criação de novas instâncias, já que é possível replicar exatamente o mesmo ambiente sempre que necessário.

Snapshots EBS

Durante o laboratório também aprendi sobre os Snapshots EBS.

Os Snapshots são utilizados para criar backups dos volumes de armazenamento das instâncias EC2. Caso ocorra algum problema, esses backups permitem restaurar os dados com mais segurança.

É um recurso importante para proteger informações e facilitar a recuperação do ambiente.

Escalabilidade

Um dos assuntos mais importantes foi entender os dois tipos de escalabilidade.

Escalabilidade Vertical

Consiste em aumentar ou diminuir os recursos da mesma instância, como CPU e memória.

Escalabilidade Horizontal

Consiste em adicionar novas instâncias para distribuir a carga de trabalho entre elas.

Esse modelo normalmente é utilizado junto com serviços como Auto Scaling e Load Balancer.

Instâncias Spot

Aprendi que as Spot Instances são instâncias disponibilizadas pela AWS com um custo muito menor que as instâncias On-Demand.

A principal vantagem é o preço reduzido, porém elas podem ser interrompidas pela AWS caso os recursos sejam necessários para outros clientes.

Por isso, são mais indicadas para tarefas que podem ser interrompidas sem causar prejuízos.

O que achei mais interessante

O que mais chamou minha atenção foi a facilidade que a AWS oferece para criar servidores em poucos minutos e aumentar ou diminuir recursos conforme a necessidade da aplicação.

Também achei interessante a possibilidade de criar uma AMI para reutilizar um ambiente já configurado e utilizar Snapshots para manter backups dos dados de forma simples.

Conclusão

Este laboratório me ajudou a entender melhor como funciona o gerenciamento de instâncias EC2 na AWS. Aprendi conceitos importantes como AMIs, Snapshots EBS, escalabilidade vertical e horizontal e os diferentes tipos de instâncias disponíveis. Esses conhecimentos serão úteis para futuros projetos utilizando computação em nuvem e também servem como base para continuar estudando outros serviços da AWS.
