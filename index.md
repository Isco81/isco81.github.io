---
layout: default
title: "IRC to Discord Bridge Bot: Sync Messages Effortlessly 🌉🤖"
description: "Bridge IRC and Discord with this Python bot"
---
# IRC to Discord Bridge Bot: Sync Messages Effortlessly 🌉🤖

![IRC Discord Bridge](https://img.shields.io/badge/IRC_Discord_Bridge-v1.0.0-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8%2B-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## Overview

The **IRC Discord Bridge** is a powerful bot designed to synchronize messages between IRC and Discord channels. This Python-based solution allows users to communicate seamlessly across platforms, making it easier to manage communities that use both IRC and Discord. Whether you are a developer looking to enhance your community engagement or a user wanting to connect with friends across platforms, this bot provides a straightforward way to bridge the gap.

## Features

- **Message Synchronization**: Automatically relay messages between specified IRC and Discord channels.
- **User Mapping**: Map users between IRC and Discord to maintain context.
- **Multi-Channel Support**: Connect multiple IRC-Discord channel pairs.
- **Configurable Settings**: Easily adjust settings to suit your needs.
- **Open Source**: Contribute to the project or modify it for your requirements.

## Getting Started

To get started with the IRC Discord Bridge bot, follow these steps:

### Prerequisites

- Python 3.8 or higher
- An IRC server
- A Discord bot token
- Basic knowledge of Python and command-line interface

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Isco81/irc-discord-bridge-python-bot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd irc-discord-bridge-python-bot
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Configuration

Before running the bot, you need to configure it:

1. Create a configuration file named `config.json` in the project directory.
2. Add the following JSON structure to the file:

   ```json
   {
       "discord_token": "YOUR_DISCORD_BOT_TOKEN",
       "irc": {
           "server": "irc.example.com",
           "port": 6667,
           "channels": [
               "#your-irc-channel"
           ]
       },
       "discord": {
           "channels": [
               "YOUR_DISCORD_CHANNEL_ID"
           ]
       }
   }
   ```

3. Replace the placeholders with your actual Discord bot token, IRC server details, and channel IDs.

### Running the Bot

To run the bot, execute the following command:

```bash
python main.py
```

You should see log messages indicating that the bot is connecting to IRC and Discord.

## Usage

Once the bot is running, it will start relaying messages between the specified IRC and Discord channels. Users can send messages in either channel, and the bot will handle the synchronization.

### User Mapping

To ensure that messages are attributed correctly, the bot attempts to map users between IRC and Discord. If a user does not exist in the mapping, the bot will use a generic username.

### Commands

The bot supports several commands to manage its functionality:

- **!help**: Displays a list of available commands.
- **!status**: Shows the current status of the bot and connected channels.
- **!config**: Displays the current configuration settings.

## Contributing

We welcome contributions to enhance the functionality of the IRC Discord Bridge bot. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

### Code of Conduct

Please adhere to our [Code of Conduct](CODE_OF_CONDUCT.md) when contributing to this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

You can find the latest releases of the IRC Discord Bridge bot [here](https://github.com/Isco81/irc-discord-bridge-python-bot/releases). Download the latest version and execute it to get started.

## Topics

This repository covers a variety of topics, including:

- bot
- bridge
- discord
- discord-bot
- discord-irc
- discord-irc-python
- discord-irc-relay
- discord-python
- discord-python-bot
- irc
- irc-bot
- irc-discord
- irc-discord-python
- python
- python-discord
- python-discord-bot
- python-irc-bot
- relay
- syncs-messages

## Support

For support, please open an issue on GitHub. We will do our best to assist you.

## Acknowledgments

Special thanks to the contributors and the community for their support and feedback. Your contributions help make this project better.

## Additional Resources

- [Python Documentation](https://docs.python.org/3/)
- [Discord API Documentation](https://discord.com/developers/docs/intro)
- [IRC Documentation](https://en.wikipedia.org/wiki/Internet_Relay_Chat)

For further information, visit the [Releases](https://github.com/Isco81/irc-discord-bridge-python-bot/releases) section to check for updates and new features.