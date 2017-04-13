# Criando um BOT para Telegram

Utilizaremos o módulo [node-telegram-bot-api](https://github.com/yagop/node-telegram-bot-api/) para essa tarefa.

Primeira coisa que você precisa é instalar esse módulo:

```

npm i -S node-telegram-bot-api

```

E depois iniciar um arquivo `index.js` com as seguintes linhas:

```js

const TelegramBot = require( `node-telegram-bot-api` )

const TOKEN = `SEU TOKEN`

const bot = new TelegramBot( TOKEN, { polling: true } )

```

> 
> Mas onde pego esse `TOKEN` ?
> 

Click nesse manolo -> [@BotFather](https://telegram.me/botfather) <- para incicar o chat com o Bot gerenciador de Bots. <3

![@BotFather](http://i.imgur.com/vYqkBH2.png)
