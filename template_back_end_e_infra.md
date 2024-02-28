Nome Projeto - Grupo
====================

Introdução
----------

Este template de documentação fornece instruções para inicializar, desenvolver e executar um back-end .NET Core MVC com C# em Docker. Informe o que seu grupo fez e para quem.

Pré-requisitos
--------------

* Docker instalado e configurado.
* Visual Studio ou Visual Studio Code para desenvolvimento.

Inicialização do projeto
------------------------

### Obtendo o código

* Clone o repositório do projeto:

```bash
git clone https://github.com/nome-do-repositorio.git nome-do-projeto
```

* Ou faça o download do código-fonte e descompacte-o.

Construção da imagem Docker
---------------------------

* Execute o seguinte comando no terminal para construir a imagem Docker:

```bash
docker build -t nome-da-imagem .
```

Execução da aplicação
---------------------

* Execute o seguinte comando para executar a aplicação em um container Docker:

```bash
docker run -d -p 8080:80 nome-da-imagem
```

* A aplicação estará acessível em [http://localhost:8080](http://localhost:8080).

Estrutura de pastas
-------------------

```markdown
├── Controllers
│   └── ...
├── Models
│   └── ...
├── Views
│   └── ...
├── Properties
├── wwwroot
│   └── ...
├── appsettings.json
├── Program.cs
├── Startup.cs
└── nome-do-projeto.csproj
```

Integrantes do projeto
----------------------

* Aluno 1 (linkedin)
* Aluno 2 (linkedin) ...

Demais itens
------------

### Tecnologias utilizadas

* .NET Core
* C#

### Bibliotecas e Frameworks

* Entity Framework Core
* ASP.NET Core MVC

### Deploy

* Onde está feito o deploy da aplicação

### Links úteis

* link 1
* link 2

Apêndice
--------

```bash
Apêndice
```