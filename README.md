# Sowing Taker Auto Bot

An automated farming bot designed to interact with the Taker Sowing Protocol. This bot helps automate daily sign-ins and farming activities to accumulate Taker Points, which may be valuable for future airdrops.

## Register

- Link : https://sowing.taker.xyz

## Features

- Automatic daily sign-ins
- Support for multiple wallets
- Proxy support for advanced users
- Real-time terminal UI with status updates
- Automatic token refreshing
- Countdown timers for next farming opportunities

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Setup

1. Clone the repository:

```bash
git clone https://github.com/TestnetMaster29/Sowing-Taker-Bot.git
cd Sowing-Taker-Bot
```

2. Install dependencies:

```bash
npm install
```

3. Cp  `.env` file in the project root directory and add your private keys:

```bash
cp .env.example .env
```
```
PRIVATE_KEY_1=your_private_key_here
PRIVATE_KEY_2=another_private_key_here
# Add more as needed
```

4. (Optional) If you want to use proxies, create a `proxies.txt` file and add one proxy per line:

```
username:password@host:port
host:port:username:password
http://username:password@host:port
# Add more as needed
```

## Usage

Start the bot with:

```bash
npm start
```

### Controls

- **Q**: Quit the application
- **R**: Refresh authentication tokens
- **←**: Switch to previous wallet
- **→**: Switch to next wallet

## How It Works

1. The bot authenticates each wallet using Ethereum signatures
2. It performs daily sign-ins to earn Taker Points
3. The UI displays current points, consecutive sign-ins, and time until next farming opportunity
4. The bot automatically refreshes tokens when needed and keeps track of each wallet's status

## Security Notes

- Never share your `.env` file or private keys
- This bot runs locally and doesn't send your private keys to any external servers
- All signatures are created locally using the ethers.js library

## Troubleshooting

If you encounter any issues:

1. Make sure your private keys are correctly formatted
2. Check if your proxies (if used) are working properly
3. Ensure you have a stable internet connection
4. Try refreshing tokens using the **R** key

## Disclaimer

This bot is provided for educational purposes only. Use at your own risk. The developers are not responsible for any potential risks, including but not limited to financial losses, associated with using this software.

## License

Last updated: Sun Jun 29 12:40:07 UTC 2025


