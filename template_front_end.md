# Nome Projeto - Grupo

## Introdução

Este template de documentação fornece instruções para inicializar, desenvolver e executar um front-end Angular 17 com Node 20.11.1 em Docker. Informe oque seu grupo fez e para quem

## Pré-requisitos

- Docker instalado e configurado.

## Inicialização do projeto
### Obtendo o código

- Clone o repositório do projeto:

```bash
git clone https://github.com/nome-do-repositório.git nome-do-projeto
```

- Ou faça o download do código-fonte e descompacte-o.

## Construção da imagem Docker

- Execute o seguinte comando no terminal para construir a imagem Docker:
```bash
docker build .
```

## Execução da aplicação

- Execute o seguinte comando para executar a aplicação em um container Docker:
```bash
docker run -it -p 8080:80 nome-da-imagem
```
- A aplicação estará acessível em http://localhost:8080.

## Estrutura de pastas
```markdown
├── app
│   ├── app.component.css
│   ├── app.component.html
│   ├── app.component.spec.ts
│   ├── app.component.ts
│   ├── app.module.ts
│   ├── main.ts
│   └── styles.css
├── assets
│   └── ...
├── environments
│   ├── environment.prod.ts
│   └── environment.ts
├── Dockerfile
├── node_modules
├── package-lock.json
├── package.json
├── README.md
└── tsconfig.json
```
## Integrantes do projeto

- Aluno 1 (linkedin)
- Aluno 2 (linkedin)
...

## Demais itens

### Tecnologias utilizadas

- tec 1
- tec 2

### Bibliotecas e Frameworks

- lib 1
- lib 2

### Deploy

- Onde está feito o deploy da aplicação

### Links úteis

- link 1
- link 2

## Apêndice

```bash
Apêndice
```