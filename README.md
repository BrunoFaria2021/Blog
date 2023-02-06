<h1 align="center">:file_cabinet: My BlogApi.ASPNET</h1>

## :memo: Descrição

Este projeto é um exemplo prático do módulo 3 dos Fundamentos ASP.NET 6 do balta.io. Ele apresenta uma implementação eficiente do 
Swagger, tornando mais fácil a visualização dos métodos criados. Com muito trabalho e estudo, este projeto tem sido usado como base para a jornada na Carreira Desenvolvedor Backend .NET, evidenciando a 
evolução e crescimento do desenvolvedor. Não perca a chance de ver o resultado desse incrível projeto!.
Recentemente foi feita uma atualização nesse projeto aplicando novas metodologias adquirida do Curso do Balta.io essas metodologias Inclui autenticação/autorização por token, JWT, injeção de dependência, registro de usuários seguros e implementação de ApiKey. 

<a href="https://www.linkedin.com/in/bruno-faria-2010-45875016a" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 


## :books: Funcionalidades

Objetivo do projeto é demonstrar como utilizar as APIs, Este é o funcionalidade do controlador de categoria do blog. Este controlador oferece as seguintes funcionalidades:

Obter todas as categorias (GET v1/categories)

Obter categoria por ID (GET v1/categories/{id:int})

Criar uma categoria (POST v1/categories)

Atualizar uma categoria (PUT v1/categories/{id:int})

Excluir uma categoria (DELETE v1/categories/{id:int})

Todas as requisições retornam um ResultViewModel com os dados da categoria ou uma mensagem de erro se algo der errado..

## ✔️ :wrench: Tecnologias / Metodologias utilizadas
 
* <img align="center" alt="Bruno-Csharp" height="80" width="80" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">
* <img align="center" alt="Docker" height="80" width="80"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original-wordmark.svg" />
* <img align="center" alt="Azure" height="80" width="80" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-plain-wordmark.svg" />
   
* Microsoft.AspNetCore.Mvc;

* Microsoft.EntityFrameworkCore;

* AspNetCore  Version="7.0.2"
  

## :rocket: Rodando o projeto

Para rodar o repositório é necessário clonar o mesmo, e sera nessario fazer migrations eu usei o docker com azure então no proprio projeto
executei esses comando listado a baixo que ja criou o banco e as tabelas.

=> dotnet ef migrations add CreateDatabase

=>dotnet ef database update Finalizando esse comando ja pode executar e testar o projeto.


## :handshake: Colaboradores
Meu linkedin <a href="https://www.linkedin.com/in/bruno-faria-2010-45875016a" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 

## :dart: Status do projeto
<p align="
LEFT
">
<img src="http://img.shields.io/static/v1?label=STATUS&message=Em - desenvolvimento &color=GREEN&style=for-the-badge"/>
</p>
