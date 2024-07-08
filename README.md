# RabbitMQ-Linkedin
[![NodeJS](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/en) [![RabbitMQ](https://img.shields.io/badge/rabbitmq-%23FF6600.svg?&style=for-the-badge&logo=rabbitmq&logoColor=white)](https://www.rabbitmq.com/) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

## Cosa installare
```
npm init
npm i dotenv child_process express amqplib
```

## Configura il file config.env
All'interno del file `config.env` inserisci i tuoi dati per poter accedere al server di RabbitMQ con i tuoi dati di accesso 
```
##############################
#   File di configurazione   #
##############################

IP_address = 192.168.2.163 # IP address of the Main RabbitMQ Server
IP_port = 5672 # default port for RabbitMQ
WebSocket_port = 8080 # default port for WebSockets
username = raspberry
password = raspberry
queue_numbers = numeri_da_calcolare # name of the queue for the numbers to be calculated
queue_results = risultati_calcolo # name of the queue for the results of the calculations
```
