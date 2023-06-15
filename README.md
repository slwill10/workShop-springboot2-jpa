# Projeto: WorkShop Spring Boot 3 JPA
Este projeto é um exemplo de aplicativo desenvolvido com o uso do framework Spring Boot 3 e da tecnologia JPA (Java Persistence API). O objetivo do projeto é demonstrar a criação de uma aplicação web utilizando essas tecnologias, juntamente com o banco de dados H2 para ambiente de desenvolvimento, PostgreSQL para ambiente de produção, o cliente Postman para testes de API e a plataforma de hospedagem Heroku para implantação do aplicativo.

## Ferramentas utilizadas
Spring Boot 3: Framework Java para criação de aplicativos web e serviços RESTful.
H2: Banco de dados em memória para ambiente de desenvolvimento.
Postman: Cliente para testes de APIs.
PostgreSQL: Banco de dados relacional para ambiente de produção.
Heroku: Plataforma de hospedagem em nuvem.
## Configuração do projeto
Faça o clone deste repositório para a sua máquina local.
Importe o projeto em sua IDE de preferência como um projeto Maven.
Certifique-se de ter o Java JDK e o Maven instalados em sua máquina.
Configure as dependências necessárias no arquivo pom.xml para as ferramentas que serão utilizadas (Spring Boot, H2, Postman, PostgreSQL).
Realize as configurações de conexão com o banco de dados no arquivo application.properties ou application.yml do projeto, dependendo da sua preferência.
Execute a aplicação para iniciar o servidor embutido do Spring Boot.
## Utilizando o H2 para ambiente de desenvolvimento
Durante o desenvolvimento, o projeto utilizará o banco de dados H2 em memória. O H2 é uma ótima opção para testes e desenvolvimento, pois não requer a instalação de um servidor de banco de dados separado. Ele será configurado automaticamente pelo Spring Boot.

## Utilizando o Postman para testes de API
O Postman é uma ferramenta popular para testar APIs RESTful. Com ele, você pode enviar requisições HTTP para a aplicação e verificar as respostas recebidas. No projeto, você encontrará uma coleção de requisições do Postman (workShop-springboot3-jpa.postman_collection.json) que poderá importar para o Postman e usar para testar as APIs do projeto.

## Utilizando o PostgreSQL para ambiente de produção
Quando você estiver pronto para implantar o aplicativo em um ambiente de produção, é recomendado configurar o banco de dados PostgreSQL. No arquivo application.properties ou application.yml, atualize as configurações do banco de dados para usar o PostgreSQL em vez do H2.

## Implantação no Heroku
O Heroku é uma plataforma de hospedagem em nuvem que permite implantar aplicativos facilmente. Para implantar o projeto neste ambiente, siga as instruções do Heroku para criar um novo aplicativo e conectar o repositório do GitHub ao aplicativo. O Heroku deve ser configurado para usar o PostgreSQL como banco de dados em produção.

## Contribuição
Sinta-se à vontade para contribuir com melhorias, correções de bugs ou novos recursos para este projeto. Basta enviar um pull request para ser analisado.

## Licença
Este projeto está licenciado sob a MIT License.
