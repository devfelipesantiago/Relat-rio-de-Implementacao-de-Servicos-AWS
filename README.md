# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 15/08/2023
Empresa: Abstergo Industries 
Responsável: Felipe Santiago

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Felipe Santiago. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- S3 Intelligent-Tiering
- É recomendado para dados com padrões de acesso desconhecidos ou com padrões difíceis de prever. É ideal para conjuntos de dados em que você pode não conseguir prever esses padrões de acesso. O S3 Intelligent-Tiering também pode ser usado para armazenar novos arquivos onde, logo após serem criados, seu acesso é frequente, mas diminui com o tempo. Isso permite mover os dados para o S3 One Zone-IA ou arquivá-los no S3 Glacier.
- A quantidade de dados que será utilizado parece ser variavel de acordo com as informações recibidas, assim quanto houver a variação de dados o S3 pode se adequar à quantiadade de dados que for necessária.

Etapa 2: 
- AWS Instance Scheduler
- O AWS Instance Scheduler é uma solução simples criada pela AWS que permite aos clientes configurar facilmente agendamentos personalizados para iniciar e parar seu Amazon Elastic Compute Cloud (Amazon EC2) e Amazon Relational Database Service (Amazon RDS).
- Por exemplo, você pode criar um cronograma para executar suas instâncias apenas durante o horário comercial, de segunda a sexta-feira, das 9h às 17h, em um determinado fuso horário. Isso pode resultar em uma economia de até 76% em comparação com a execução dessas instâncias 24 horas por dia2. Você também pode criar um cronograma para parar suas instâncias após o horário de trabalho, para garantir que as instâncias de desenvolvimento estejam desligadas até que sejam necessárias novamente.

Etapa 3: 
- Amazon RDS (Relational Database Service)
- O Amazon RDS é um serviço web que facilita a configuração, operação e dimensionamento de um banco de dados relacional na Nuvem AWS. Ele fornece capacidade econômica e redimensionável para um banco de dados relacional padrão do setor e gerencia tarefas comuns de administração de banco de dados. Com o Amazon RDS, você pode escolher entre vários mecanismos de banco de dados amplamente usados, incluindo Amazon Aurora compatível com MySQL, Amazon Aurora compatível com PostgreSQL, MySQL, MariaDB, PostgreSQL, Oracle e SQL Server. Você também pode implantar no local com o Amazon RDS no AWS Outposts. O Amazon RDS elimina muitas das tarefas demoradas e complexas associadas ao autogerenciamento de seus bancos de dados, liberando você para se concentrar na criação e execução de seus aplicativos. Alguns dos benefícios de usar o Amazon RDS incluem backups automáticos, aplicação automática de patches de software e fácil dimensionamento de recursos de computação e armazenamento.
- A empresa pode usar o Amazon RDS para hospedar seu banco de dados de clientes. Em vez de ter que configurar e gerenciar um servidor de banco de dados localmente, a empresa pode simplesmente criar uma instância do Amazon RDS e começar a usar o banco de dados imediatamente. O Amazon RDS cuida de tarefas como backups automáticos, aplicação de patches de software e escalonamento de recursos computacionais e de armazenamento.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado diminuir os custos, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Felipe Santiago
