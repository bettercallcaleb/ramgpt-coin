# RAMGPT Coin (RAMG)

RAMGPT Coin is a minimal fixed-supply ERC-20 token.

## Token

- Name: RAMGPT Coin
- Symbol: RAMG
- Standard: ERC-20
- Decimals: 18
- Total supply: 1,000,000,000 RAMG
- Minting after deployment: No
- Owner/admin privileges: None
- Transfer tax: None
- Blacklist/freeze functions: None

The entire fixed supply is minted to the deployer address at deployment.

## Base Sepolia Deployment

- Network: Base Sepolia Testnet
- Chain ID: 84532
- Contract: `0xD38F9B6B27Aa377B84eceDdc47f0b4659425a104`
- Explorer: https://sepolia.basescan.org/address/0xD38F9B6B27Aa377B84eceDdc47f0b4659425a104
- Deployer: `0xFc4b9871e80C2A4Acb98003dD7CB21c414137Ba1`
- Status: Deployed and source-verified through Remix

This deployment is on a test network and has no monetary value.

## Contract

`contracts/RAMGPTCoin.sol`

The contract is based on OpenZeppelin Contracts ERC20.

## Deploy with Remix

1. Open Remix.
2. Clone this repository or open `contracts/RAMGPTCoin.sol`.
3. Compile with Solidity 0.8.20 or a compatible 0.8.x compiler.
4. Connect a wallet.
5. Select the intended network.
6. Deploy and verify the source code on the relevant block explorer.

## Security

This repository contains a deliberately minimal ERC-20 implementation. No security audit is implied.

## License

MIT
