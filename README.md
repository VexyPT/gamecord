# **GAMECORD**

> **Gamecord é um poderoso pacote npm com uma coleção de minijogos para o seu bot discord :)**
(Versão traduzida do discord-gamecord)


## **⚙️ Installation** 
```
npm i gamecord@latest
```


## **✨ Características**

- Fácil de usar.
- Amigável para iniciantes.
- Jogos de comandos de barra.
- Suporta Discord.js v14.


## **📚 Uso**
```js
const { Slots } = require('gamecord');

const Game = new Slots({
    message: interaction,
    isSlashGame: true,
    embed: {
        title: 'Slot Machine',
        color: '#5865F2'
    },
    slots: ['🍕','🍔','🍟','🌭','🍿']
});

Game.startGame();
Game.on('gameOver', result => {
    console.log(result);
});
```


## **📷 Pré-visualização**
Em breve

## **❔ Suporte**
Em breve