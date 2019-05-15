# IT Club Discord Bot

This is the Discord bot for the Infomation Technlolgy Club of Ivy Tech Community Colllege.

# Requirment
1. Node.js
2. Npm
3. Download Here: https://nodejs.org/en/


## Installation

Use whatever perfer shell command to make the folder that will house the bot.

```bash
mkdir test-bot
```

Use the package manager [npm](https://www.npmjs.com/) to initalize npm and install the discord API Library.

```bash
npm init -y
```


```bash
npm install discord.js
```

## Usage

Naviagate to Discord Developer Portal [Discord](https://discordapp.com/developers/applications/) to establish a web socket

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Testing
To test the bot on your local machine please add the following to the package.json file.

```bash
npm install nodemon --save-dev
```

After install nodemon, which relode the code as soon changes are saved and deteced. Add the following below to the package.json file.

```
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js",
    "dev": "nodemon index.js"
  },
```

To load the bot run 

```bash
npm run dev
```
