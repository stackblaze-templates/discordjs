# Discord.js Bot
Discord bot built with discord.js (JavaScript).
## Local Development

    cp .env.example .env
    # Add your bot token and client ID
    npm install
    npm run deploy-commands  # Register slash commands
    npm start

## Adding Commands
Add slash commands in commands/. See commands/ping.js.
Add event handlers in events/.
## Deploy on StackBlaze
This template includes a stackblaze.yaml. Set DISCORD_TOKEN and CLIENT_ID.
