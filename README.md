# Cards MS

## _Gerenciador de Pensamentos_

Com essa aplicação podemoso listar, cadastrar, editar e excluir um pensamento.

**Requisitos**

[Spring Boot](https://start.spring.io/) versão >= 3.2.0.

[Docker](https://www.docker.com/get-started/) versão >= 24.0.6

[PostgreSQL](https://www.postgresql.org/download/) versão >= 15.5 - Apenas para referência, na instalação utilizamos uma versão conteinizada.

[Angular CLI](https://angular.dev/) versão >= 17.0.5.

[Node](https://nodejs.org/en) versão >= 20.10.0.

**Para mais detalhes verifique as aplicações separadas**

[Cards API](https://github.com/mibess/card-api) Aplicação backend Spring Boot.
[Mibess Frontend](https://github.com/mibess/mibess-cards) Aplicação frontend Angular.

**Acesse o Projeto em Produção no link abaixo**

### Cards -> https://cards.mibess.com.br/

# Instalação

1 - Clone o repositório do GitHub

```
git clone --recurse-submodules https://github.com/mibess/cards-ms.git
```

2 - Agora vamos instalar o npm, entre na pasta do frontend

```
cd cards-ms/mibess-cards
```

```
npm install
```

3 - Voltamos para a pasta cards-ms e executamos o comando

```
cd ..
```

```
docker compose up -d --build
```

4 - Acesse a aplicação no link

http://localhost:80

Lembrando que as portas:
**54321** - Postgres
**8080** - Backend
**4200** - Frontend
**80** - Nginx
Devem estar disponíveis

### Agora você deve estar pronto para usar o Mibess Cards localmente em sua máquina!
