Para rodar o projeto, na raiz execute:
`docker compose up --build -d`

Para executar comandos npm (como npm install, por exemplo) utilize:
`docker compose run --rm npm {comando}`

Para subir o container depois de ter executado o build uma vez:
`docker compose start`

Extensões para o vs-code:

- [Vue Volar extension Pack][def] (Pacote com todas as extensões necessárias)

[def]: https://marketplace.visualstudio.com/items?itemName=MisterJ.vue-volar-extention-pack

Para rodar o projeto SEM DOCKER, na pasta vue-app execute:
`npm run dev`

Lembrar de executar antes:
`npm install`