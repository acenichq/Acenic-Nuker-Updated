# Acenic Nuker

**Acenic Nuker** is a powerful Discord nuke tool designed to simplify the process of banning users, deleting channels, and mass managing servers. This tool is created for educational purposes and should be used responsibly in controlled environments.

## Features

- **Channel Deletion:** Mass delete channels quickly and efficiently.
- **Role Deletion:** Remove roles from the server.
- **Member Management:** Kick or ban all users with customizable options.
- **Nuke Server:** An all-in-one command to nuke the server by deleting all channels, roles, and optionally banning users.
- **User-Friendly Interface:** Simplified commands for easier use.

## Requirements

- Python 3.x
- `discord.py` (Ensure you are using the correct version of `discord.py` for token-based access)
- Your Discord account token (Note: This project uses account tokens, not bot tokens)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/acenichq/Acenic-Nuker-Updated.git
   cd Acenic-Nuker
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure the settings in `config.json` (or relevant configuration file):
   - Add your Discord account token.
   - Configure other settings like server ID, user limits, etc.

4. Run the script:
   ```bash
   python bot.py
   ```

## Commands

- `.nuke` - Deletes all channels and roles in the server.
- `.banall` - Bans all users in the server.
- `.kickall` - Kicks all users in the server.
- `.deletechannels` - Deletes all channels.
- `.deleteroles` - Deletes all roles.
  

## Legal Disclaimer

This tool is for **educational purposes only**. The developers of Acenic Nuker are not responsible for any misuse of this tool. Be mindful of Discord’s terms of service and the legal implications of using this tool inappropriately.

## Support

For more information, tutorials, and support, join our [Discord server](https://discord.gg/7fDuWHSkYj) or check out the [Acenic Studio YouTube channel](https://www.youtube.com/@Acenic.studio).
