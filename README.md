# 🔥 Discord Nuke Bot

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![discord.py](https://img.shields.io/badge/discord.py-2.3.0+-blue.svg)](https://github.com/Rapptz/discord.py)
[![License](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)

**⚠️ WARNING: This tool is for educational purposes only. Misuse may violate Discord's Terms of Service and could result in account termination. ⚠️**

</div>

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Commands](#commands)
- [Rate Limiting](#rate-limiting)
- [Disclaimer](#disclaimer)
- [License](#license)

## 🎯 Overview

Discord Nuke Bot is a powerful automation tool designed for server stress testing and security auditing. It demonstrates the potential impact of compromised administrator privileges and helps server owners understand the importance of proper permission management.

## ✨ Features

- **Complete Server Wipe**: Deletes all channels and roles simultaneously
- **Mass Channel Creation**: Creates up to 100+ text channels instantly
- **Message Spamming**: Sends thousands of messages with rate limit handling
- **Role Flooding**: Generates hundreds of roles automatically
- **Customizable Messages**: Configure spam content via environment variables
- **Random Channel Names**: Use randomized names from a custom list
- **Rate Limit Protection**: Smart rate limiting to avoid API blocks
- **Config Display**: View current configuration in Discord

## 📦 Prerequisites

- Python 3.8 or higher
- Discord Bot Token with Administrator permissions
- Discord Developer Application

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/discord-nuke-bot.git
cd discord-nuke-bot
