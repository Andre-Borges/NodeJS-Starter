## NodeJS Starter - Rocketseat

- API em Node utilizando MongoDB.

## Configuração

1. Caso não tenha, instale o [Docker](https://www.docker.com/get-started)

2. Instalação / Configuração do MongoDB:

	```sh
	$ docker pull mongo
  $ docker run --name mongodb -p 27017:27017 -d mongo
  $ docker start mongodb
	```

3. Instale todas as dependências:

	```sh
	$ npm install
	```
  
4. Rode o projeto:

	```sh
	$ npm run dev
	```
