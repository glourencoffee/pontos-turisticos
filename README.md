# Sobre

Este repositório contém uma mini-aplicação web que lista pontos turísticos
cadastrados pelo usuário. O repositório está dividido em duas pastas, `client`,
que contém o código do front-end da aplicação, desenvolvido com React, e `server`,
que contém o código do back-end da aplicação, desenvolvido com Express.js e SQLite.

# Requisitos

A aplicação utiliza Node.js e npm, então é preciso tê-los instalados para continuar.
Para baixar o Node.js, visite https://nodejs.org/.

Durante o desenvolvimento, foram utilizados Node.js e npm nas versões 18.10 e 8.19,
respectivamente.

# Uso

## Cliente

Para compilar a aplicação web, vá para o diretório `client` e execute `npm run build`:

```sh
> cd client
> npm run build
```

Após o procedimento, a aplicação estará disponível no diretório `dist`. Use `npm run preview`
para rodar um servidor que servirá a aplicação compilada.

Alternativamente, pode-se rodar a aplicação em modo de desenvolvimento:

```sh
> cd client
> npm run dev
```

Em ambos os casos, o website ficará disponível localmente num endereço informado no terminal
(e.g. "http://localhost:5173/").

## Servidor

O procedimento é semelhante para o servidor, exceto que este se encontra no diretório
`server` e é executado com o comando `npm run start`:

```sh
> cd server
> npm run start
```

Isso fará o servidor rodar na porta padrão 8000 (http://localhost:8000/). O servidor
também pode rodar em versão de desenvolvimento com `npm run dev`.