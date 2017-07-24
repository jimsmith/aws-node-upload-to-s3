# AWS-NODE-UPLOAD-TO-S3

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://github.com/guivirtuoso/aws-node-upload-to-s3/blob/master/LICENSE)

Formulário simples para envio de arquivos para o S3

### Pré-requisitos
- Criar um usuário no IAM com ```Programmatic access``` apenas e definir um grupo de permissões com acesso completo no S3

- Salvar os dados relacionados ao ```awsAccessKeyId``` e ```awsSecretAccessKey```, você irá precisar destas informações na próxima etapa

- Criar um bucket no S3 e [definir as propriedades de static website hosting](http://docs.aws.amazon.com/pt_br/AmazonS3/latest/user-guide/static-website-hosting.html)

- Instalar o [NodeJS](https://nodejs.org/en/download/)

### Configurações
- Definir as propriedades do arquivo ```/resources/aws.properties```

- Use os dados salvos no passo anterior para preencher as propriedades do usuário

- ```CUIDADO``` Não salve em repositórios públicos suas informações de ```awsAccessKeyId``` e ```awsSecretAccessKey```

### Processo de build
Acessar a pasta do projeto via terminal e executar os comandos abaixo:
- ```npm install```

- ```node build.js```

### Instalação
- Fazer upload dos arquivos gerados no ```/target``` para o seu bucket

- Criar no bucket uma pasta com o mesmo nome definido na propriedade ```bucketDestinyFolder```

### Créditos
Adaptação do projeto de [Christoph Gysin](mailto:christoph.gysin@gmail.com) [(Github)](https://github.com/serverless/examples/tree/master/aws-node-upload-to-s3-and-postprocess)
