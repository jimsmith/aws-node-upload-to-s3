# AWS-NODE-UPLOAD-TO-S3
Formulário simples para envio de arquivos para o S3

### Pré-requisitos
- Criar um bucket no S3 e definir as propriedades de WebHosting
- Instalar o NodeJS

### Configurações
- Definir as propriedades do arquivo ```/resources/aws.properties```

### Processo de build
Rodar os comandos abaixo na pasta do projeto
- ```npm install```
- ```node build.js```

### Instalação
- Colocar no bucket os arquivos gerados no ```/target```


### Créditos
Adaptação do projeto de [Christoph Gysin](mailto:christoph.gysin@gmail.com) [(Github)](https://github.com/serverless/examples/tree/master/aws-node-upload-to-s3-and-postprocess)
