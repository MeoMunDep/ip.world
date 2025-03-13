# 🚀 Bot Setup Instructions

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux.)

Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly. This guide is designed to be beginner-friendly, with clear explanations for each step.

---

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
   - [`configs.json`](#1-configsjson)
   - [`datas.txt`](#2-datastxt)
   - [`wallets.txt`](#3-walletstxt)
   - [`proxies.txt`](#4-proxiestxt)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

## Prerequisites

Before running the bot, make sure you have the following installed:

- **Python** (Version: `3.11.9`)
- **pip** (Version: `24.3.1`)

Download Python and pip here: [Download Link](https://t.me/KeoAirDropFreeNe/257/2627).

---

## Installation Steps

1. **Download and Extract the Bot Files:**

   - Extract the bot package into a folder on your computer.
     -> Double click on `setup.bat` for windows or `setup.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

2. **Install Dependencies:**
   Open your terminal or command prompt, navigate to the folder where the bot files are located, and run:

   ```bash
   pip install aiohttp requests cloudscraper pycryptodome fake-useragent aiohttp-proxy colorama bs4
   ```

3. **Prepare Configuration Files:**
   - Ensure all configuration files are set up correctly before running the bot (see [Configuration Files](#configuration-files) section).

---

## Configuration Files

### 1. `configs.json` - 📜 Adjust Bot Settings

This file controls the bot’s behavior. Below is an example configuration:

```json
{
  "timeZone": "en-US",
  "skipInvalidProxy": false,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100
}
```

- **Fields Explained:**
  - `timeZone`: Time zone setting (e.g., "en-US").
  - `skipInvalidProxy`: Skip invalid proxies if `true`.
  - `delayEachAccount`: Random delay range (in seconds) between accounts.
  - `timeToRestartAllAccounts`: Time (in seconds) to restart all accounts.
  - `howManyAccountsRunInOneTime`: Number of accounts to run simultaneously.

### 2. `datas.txt` - 🗂️ User Data

Fill the `datas.txt` file with your emails's address. This file contains user data in the following format:

```txt
adsa@gmail.com
adsa@gmail.com
adsa@gmail.com
```

_Note: Each row for each account_

### 3. `wallets.txt` - 💼 Wallet Addresses

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

Add your wallet addresses in the following format:

```txt
abc...xyz
abc...xyz
abc...xyz
```

_Note: Wallet updates are currently not supported._

### 4. `proxies.txt` - 🌐 Proxy List (Optional)

If you are using proxies, add them here. Leave the file blank if you are not using proxies. Supported formats:

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

_Note: each row for each account_

---

## Running the Bot

1. Navigate to the folder containing the bot files:

   ```bash
   cd /path/to/bot-folder/
   ```

2. Run the bot using the following command:

   ```bash
   python meomundep.py
   ```

   or

   ```bash
   python3 meomundep.py
   ```

   or

   ```bash
   py meomundep.py
   ```

   or

   ```bash
   py3 meomundep.py
   ```

---

## Contact and Support

- **Help me with your referral** [Referral Link](https://ip.world/)
- **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801) or [Here](https://github.com/MeoMunDep/MeoMunDep)

If you encounter any issues or have questions, feel free to reach out:

- **Contact:** [Contact Me](https://t.me/MeoMunDep)
- **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)
- **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

Your support is greatly appreciated! 🐱

---

Enjoy using the bot! 🚀
