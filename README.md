## 📢 Discord Broadcast Bot

A clean and powerful Discord broadcast bot built with **Discord.js v14**. It allows you to send broadcast messages to all server members or specific roles. Designed to be lightweight, fast, and easy to extend.

  




---

## Features

* Send broadcast messages to all members or specific roles
* Lightweight and fast
* Built with Discord.js v14
* Easy to customize and extend

---

## Requirements

* Node.js 16.9+
* Discord Bot Token

### Packages Used

```bash id="pkg001"
@discordjs/builders

@discordjs/rest

discord-api-types

discord.js
```

---

## Installation

Clone the repository and install dependencies:

```bash id="inst002"
git clone https://github.com/your-username/discord-broadcast-bot

cd discord-broadcast-bot

npm install
```

Create a `.env` file:

```env id="env003"
TOKEN = here 

CLIENT_ID = here ID Bot

GUILD_ID = here ID Server
```

Start the bot:

```bash id="run004"

npm start

```

---

## Commands

* `broadcast` — Send a broadcast message
  
* `ping` — Check bot status

---

## Project Structure

```bash id="struct005"
discord-broadcast-bot/
│── index.js
│── commands/
│   └── broadcast.js
│── package.json
│── README.md
└── .env
```

---

## Contributing

Contributions are welcome. Feel free to open an issue or submit a pull request.
