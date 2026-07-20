
# O que aprendi

Durante este laboratório consegui entender melhor como funciona o Amazon EC2 e sua importância dentro da AWS. Também aprendi conceitos relacionados ao gerenciamento de instâncias, criação de imagens AMI, utilização de Snapshots EBS e escalabilidade.

---

# Amazon EC2

O Amazon EC2 (Elastic Compute Cloud) é um serviço que permite criar servidores virtuais na nuvem.

Com ele é possível:

- Hospedar aplicações;
- Criar ambientes de desenvolvimento;
- Executar servidores web;
- Realizar testes;
- Aumentar ou reduzir recursos conforme a necessidade.

Aprendi também que existem diferentes tipos de instâncias, cada uma voltada para um tipo de carga de trabalho.

---

# Escalabilidade

Um dos conceitos mais importantes foi entender a diferença entre os dois tipos de escalabilidade.

## Escalabilidade Vertical

Consiste em aumentar ou diminuir os recursos da mesma instância.

Exemplo:

- Mais CPU;
- Mais memória RAM.

É utilizada quando uma única máquina precisa de mais desempenho.

---

## Escalabilidade Horizontal

Consiste em adicionar novas instâncias para dividir a carga entre elas.

Esse modelo é muito utilizado junto com:

- Auto Scaling;
- Elastic Load Balancer.

---

# Amazon Machine Image (AMI)

Aprendi que uma AMI é uma imagem completa de uma instância.

Ela pode conter:

- Sistema operacional;
- Aplicações instaladas;
- Configurações;
- Dependências.

Sua principal vantagem é permitir criar novas instâncias exatamente iguais à original, economizando tempo na configuração.

---

# Snapshots EBS

Os Snapshots EBS são utilizados para realizar backups dos volumes de armazenamento.

Com eles é possível:

- Restaurar dados;
- Criar novos volumes;
- Recuperar ambientes;
- Garantir maior segurança das informações.

---

# Instâncias Spot

Outro conceito interessante foi o das Spot Instances.

Essas instâncias possuem um custo reduzido porque utilizam capacidade ociosa da AWS.

Sua principal desvantagem é que podem ser interrompidas pela própria AWS a qualquer momento.

São indicadas para:

- Processamentos em lote;
- Testes;
- Renderização;
- Machine Learning.

---

# Principais conhecimentos adquiridos

Ao concluir este laboratório consegui compreender melhor:

- O funcionamento do Amazon EC2;
- Diferença entre escalabilidade vertical e horizontal;
- Como utilizar AMIs;
- A importância dos Snapshots EBS;
- Quando utilizar Instâncias Spot;
- A estrutura básica para gerenciamento de servidores na AWS.

---

# Minha conclusão

Este laboratório foi importante para consolidar os conceitos básicos de gerenciamento de instâncias EC2.

Além de aprender sobre criação e administração de servidores na nuvem, também compreendi a importância de recursos como AMIs e Snapshots para facilitar implantações e aumentar a segurança dos ambientes.

Esses conhecimentos servirão como base para continuar estudando outros serviços da AWS e aprofundar meus conhecimentos em computação em nuvem.

---

## Tecnologias utilizadas

- Amazon EC2
- Amazon EBS
- Amazon Machine Image (AMI)
- AWS Management Console
- Git
- GitHub

---

## Referências

- Documentação oficial da AWS
- Curso "Gerenciando Instâncias EC2 na AWS" - DIO
