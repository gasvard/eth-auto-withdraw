# Installation

1. Copy the `.env.example` to `.env`, then add the following variables inside it and save the file:

- `INFURA_ID` – your Infura project ID (can sign up for free on https://infura.io to get one);
- `VAULT_WALLET_ADDRESS` — the wallet address to which the withdrawn ETH should be sent.
- `DEPOSIT_WALLET_PRIVATE_KEY` — the private key of your deposit wallet.

2. Run either `npm install` or `yarn install`.

3. Run `node index.js` to start the bot.
