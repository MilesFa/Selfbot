# Discord Self Bot

A powerful Discord self bot with multiple utility commands.

## ⚠️ DISCLAIMER / AVERTISSEMENT

**EN:**
- This self bot is for educational purposes only
- Using self bots is against Discord's Terms of Service
- I am NOT responsible for any consequences that may occur while using this self bot
- Your account may be banned if detected by Discord
- Use at your own risk
- By using this self bot, you acknowledge these risks and take full responsibility

**FR:**
- Ce self bot est à but éducatif uniquement
- L'utilisation de self bots est contre les conditions d'utilisation de Discord
- Je ne suis PAS responsable des conséquences qui peuvent survenir lors de l'utilisation de ce self bot
- Votre compte peut être banni si détecté par Discord
- Utilisez à vos propres risques
- En utilisant ce self bot, vous reconnaissez ces risques et en prenez l'entière responsabilité

## 🚀 Installation

1. Make sure you have [Node.js](https://nodejs.org/) installed
2. Clone this repository or download the files
3. Open a terminal in the project folder
4. Install dependencies:
```bash
npm install
```

## 📝 Configuration

1. Open `index.js`
2. Replace `YOUR_TOKEN_HERE` with your Discord token
3. (Optional) Modify the command prefix (default: `!`)

## 🛠️ Available Commands

- `!help` - Display commands list
- `!ping` - Show latency
- `!clear [number]` - Delete your messages
- `!userinfo [@user]` - Show user information
- `!serverinfo` - Show server information
- `!avatar [@user]` - Show avatar in full size
- `!status [online/idle/dnd/invisible]` - Change your status
- `!game [name]` - Change your game status
- `!edit [number] [text]` - Edit your recent messages
- `!autoreply [message]` - Set auto-reply for channel
- `!autoreact [emoji]` - Toggle auto-react
- `!quote [ID]` - Quote a message
- `!spam [number] [message]` - Send message multiple times
- `!dm [@user] [message]` - Send DM
- `!massdm [message]` - Send DM to all friends
- `!ghostping [@user]` - Ghost ping a user

## 🚀 Starting the Bot

To start the self bot:
```bash
npm start
```

Or use the `bot.bat` file for easy management.

## 📂 File Structure

```
Badge-Bot/
├── index.js        # Main bot code
├── package.json    # Dependencies and scripts
├── bot.bat        # Management script
└── README.md      # Documentation
```

## ⚙️ Customization

You can add your own commands by modifying `index.js`. Add a new case in the command handler switch statement.

## 🔒 Security

- NEVER share your user token
- Avoid using the self bot in a visible way
- Don't store your token in plain text (use a .env file instead)
- Be careful with mass DM and spam commands
- Some actions might be rate-limited by Discord

## 🌐 Support

This is an educational project. No support will be provided.

## ⚖️ Legal

This project is for educational purposes only. The developer assumes no liability and is not responsible for any misuse or damage caused by this program. 
