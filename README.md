# GroFi Dex


## Deployments

1. Add Key in `.env` file. It's a private key of the account that will deploy the contracts and should be gitignored.
2. u2uTestnet `KEY_TESTNET` or bsc `KEY_MAINNET`
3. add `ETHERSCAN_API_KEY` in `.env` file. It's an API key for etherscan.
4. `yarn` in root directory
5. `NETWORK=$NETWORK yarn zx v3-deploy.mjs` where `$NETWORK` is either `eth`, `goerli`, `bscMainnet`, `u2uTestnet` or `hardhat` (for local testing)
6. `NETWORK=$NETWORK yarn zx v3-verify.mjs` where `$NETWORK` is either `eth`, `goerli`, `bscMainnet`, `u2uTestnet` or `hardhat` (for local testing)