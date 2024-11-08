# Simple-Discord-Bot-
A versatile and customizable Discord bot built with Python and the `discord.py` library. This bot includes various features like dynamic status updates, easy command synchronization, and modular cog loading for additional functionality.

## 🌟 Features

- **Dynamic Status Rotation** 🔄: The bot cycles through predefined statuses every few seconds to keep the server engaged.
- **Command Synchronization** ⚙️: Automatically syncs slash commands with Discord's API without clearing previously synced commands, making it easy to update commands on the fly.
- **Modular Cog System** 🧩: Loads additional functionality from separate Python files located in the `cogs` directory, supporting a modular structure for easy expansion.

## 📋 How It Works

1. **Status Rotation**: The bot cycles through a list of statuses (e.g., "Status One", "Hello from Paradoxial") every 5 seconds using an asynchronous task loop.
2. **Command Sync**: On startup, the bot syncs slash commands with Discord, ensuring any new or modified commands are updated without disrupting the user experience.
3. **Cog Loading**: During initialization, the bot checks for a `cogs` folder and loads any `.py` files within as cogs, allowing for a modular setup and easy command management.

## 🛠️ Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/DiscordBot.git
   cd DiscordBot
