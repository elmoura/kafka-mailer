# kafka-mailer MVP

## Requisitos não funcionais

 - O serviço de mensageria deve ser um Kafka, sendo executado em um container Docker;
 - Devem ser desenvolvidos testes unitários para o envio de e-mails com Jest;
 - A lib de conexão com o Kafka deve ser a KafkaJS;

## Requisitos funcionais

 - A aplicação deverá ficar escutando eventos na fila de notificações e disparar um e-mail para o usuário;
 - Deve haver um e-mail de boas vindas, sendo formatado dinâmicamente conforme as informações do usuário;
 - Deve haver um e-mail de recuperação de senha;