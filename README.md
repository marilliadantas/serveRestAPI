# Bootcamp #01 Qualiters Club 
Teste de API Rest do manual a CI/CD 

## O que é 
Este repositório foi criado para o bootcamp de testes de API Rest. 

## Tecnologias Utilizadas
- Postman
- Node version v16.16.0
- Newman version v5.3.2
- Newman htmlextra

## Documentações
- Análise Técnica: Análise/ 
- Documento da API: [Consulte Swagger](https://serverest.dev/)

## Como instalar o ambiente
- Primeiro: Instale o node no seu computador. [baixe aqui](https://nodejs.org/en)
- Segundo: Realize a instalação do newman de forma global. [baixe aqui a dependência](https://www.npmjs.com/package/newman)
````
  npm install -g newman 
````
- Terceiro: Realize a instalação da dependência dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-html)
````
  npm install -g newman-reporter-html
````
## Como rodar os testes

### Pelo Postman web ou desktop
- Importe a collection e o environment
- Execute os testes de forma manual ou automatizada
  
### Pelo Newman
- Abra o console de preferência
- Execute a seguinte linha de comando para rodas os testes
````
  newman run ServRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
````
- Execute os testes com relatóro 
````
  newman run ServRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
````

## Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações, você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e enviroment se encontram.

## Entre em contato
[Linkedin](https://www.linkedin.com/in/marilliadantas/)
