# Teneo WebSocket Bot

An automated WebSocket client for managing multiple Teneo accounts in parallel.

## Features

- Multi-account support
- Automatic ping and reconnection
- Clean and organized logging
- Easy account management
- Colorful console output

## Prerequisites

- Node.js (version 14 or higher)
- npm (Node Package Manager)
- Teneo browser extension with registration code: `VixZZ`

## Installation

1. Clone this repository:

```bash
git clone https://github.com/dreambabyyy/TENEO.git
cd Teneosupmulty
```

2. Install dependencies:

```bash
npm install
```

## Configuration

### Getting JWT Token

1. Install Teneo browser extension
2. Register using code: `F5mxY`
3. Open extension
4. Right click > Inspect
5. Click Disconnect then Connect
6. Go to WS tab
7. Find and copy the value from the payload section

### Setting Up Accounts

1. Edit `data.txt` file in the root directory
2. Add accessToken (one per line) for each account

```
token_1
token_2

...

```
![image](https://github.com/user-attachments/assets/2e57c61c-5ad7-4262-aae8-5e17c23366b7)
## Usage

Run the bot:

```bash
node main.js
```

The bot will:

- Display a welcome banner
- Connect to all accounts in parallel
- Send pings every 10 seconds
- Show real-time points updates
- Automatically reconnect on disconnection

## Features Details

### Auto-Reconnection

- Maximum 5 reconnection attempts
- Exponential backoff delay
- Maximum delay of 30 seconds

### Error Handling

- WebSocket connection errors
- Message parsing errors
- File reading errors
- Graceful shutdown on CTRL+C

## Contributing

Feel free to submit issues and enhancement requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This tool is for educational purposes only. Use at your own risk and responsibility.


## TRAKTER
EVM : 0x59883db349d0baf6d3de4b17bea28845c007da9f 
SOL : 9GgUqQsKR2548QLmyetaszScL8LFjkGtT98ggk1Bomfg
