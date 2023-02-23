# O que é Cron?

Em um sistema operacional, existem vários comandos que executam vários tipos de tarefas. Sem eles, praticamente seria impossível o usuário navegar com tranquilidade na internet ou mesmo na área de trabalho do seu desktop. O Linux, que é um moderno sistema operacional, traz o Cron e o Crontab, que são dois comandos que auxiliam bastante o usuário. Mas o que é o Cron e o Crontab? Quais são suas aplicações? Leia esse artigo até o final e saiba tudo sobre esses dois indispensáveis comandos do Linux.

## O que é Cron e Crontab?

Esses dois comandos são, de uma maneira geral, os responsáveis pelo agendamento e execução de tarefas que o usuário espera que sejam executadas com certa regularidade. Essa constância pode ser várias vezes por minuto, hora, dia, mês ou ano. Com toda a vantagem que os scripts possibilitam em qualquer linguagem que seja escrito, todas as possibilidades se tornam praticamente infinitas.

Suponha que você precise fazer um backup de seu banco de dados MySQL, todos os dias as 6 horas da manhã. Não seria mais viável que o próprio Linux fizesse esse backup automaticamente para você? É esse tipo de comodidade que o Cron permite que você tenha. Além disso, é muito simples e basta criar um script e agendar no arquivo Crontab para que o backup seja executado todos os dias na hora estipulada por você. 

### Cron

O Cron do Linux é um programa que executa comandos ou scripts que são agendados por uma tabela chamada de Crontab. Quando é iniciado, ele procura por arquivos Crontab, com o objetivo de carregá-los na memória. Além disso, o Cron também faz a leitura do arquivo /etc/crontab e os arquivos em /etc/cron.d em busca de mais tarefas a serem executadas, como se fosse um espécie de agenda eletrônica.

Depois de carregado na memória por completo, o Cron será executado minuto por minuto, examinando todos os Crontabs armazenados e checando cada comando para saber se algo precisa ser executado naquele momento. No caso de vários usuários, cada um pode ter uma tabela Crontab diferente e o Cron saberá quando deverá executar determinada tarefa e quem será o responsável pelas mesmas.

### Crontab

Crontab é um arquivo que contém informações sobre quando um comando ou script deve ser executado e quem é o responsável pela ação. Trata-se de um arquivo de texto simples que tem um formato diferenciado para que o Cron o entenda e trabalhe em sintonia com ele. Em outras palavras, o arquivo Crontab seria uma agenda e o Cron, o dono dessa agenda que verifica minuto a minuto sem tem alguma tarefa a ser executada. Existe um comando chamado de “Crontab” que serve para criar Crontabs de acordo com a necessidade passada para ele. É ainda possível criar um Crontab para cada usuário específico, o que faz gerir melhor todos os processos, separadamente.

## Como o Magento utiliza o Cron?

A plataforma Magento se utiliza do cron para realização de tarefas de forma automática, quais são essas tarefas?

- Indexação dos indices;
- Consulta de estoque do produto;
- Listagem de produtos;
- Listagem de clientes;
- Disparos de emails;
- Consulta no banco de dados;
- Publicação de página e posts;
- Consulta de caches inválidos;

Entre outras. 

Como você pode perceber o Cron é de extrema de importância para o Magento, garanta que o crontab esteja sempre configurado e documentado.

### Dúvidas/Suporte:
Entre em contato com o nosso departamento de suporte.