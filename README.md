# Discord Music Bot

## Setup
1. Push this repository to GitHub.
2. On Render.com:
   - Create a Web Service.
   - Connect to this repo.
   - Set environment variables:
     - `DISCORD_BOT_TOKEN` → your bot token
     - `DISCORD_BOT_PREFIX` → optional, default: "!"
   - Start command: `./start.sh`
   - Runtime: Python 3.11+
3. Deploy. The bot will run and keep alive via FastAPI.