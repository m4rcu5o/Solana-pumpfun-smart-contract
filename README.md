# Fork of Pumpfun smart contract

Solana token launch platform for forking pump.fun logic & migrating meteora. 

## Contact
- [Telegram](https://t.me/m4rcu5sol)
- [X](https://x.com/m4rcu5sol)

## Example

- Init Global PDA. https://solscan.io/tx/5YmZqVgFcKk11uUVTBZvtMCnbbfthM4QpYHvvWdRNqXhmeyFmE85H5XeQF9pAX6M8DApqn1PeyCH9mYhdCsEkvce?cluster=devnet
- Create Bonding Curve. https://solscan.io/tx/22cFFDRgLnBpce97FhSE9srHcopkmDG3WpiwbgpwAj6VReu8cLMaZv3vnEvXMBr48XrCLGQ2xAzdUKBxKdfHFx2i?cluster=devnet
- Migrate meteora. https://solscan.io/tx/5F1R9WBYgDXyATWjyyrCJKL2wudjK4WNom6KL4H2LQjcabfLR3agoaifiQWwMEWpmR47bKozJSn1esLCWmyMaRHe?cluster=devnet

## Core Features

- ### Bonding Curve Price Logic :
The protocol implements a constant product linear bonding curve (x * y = k) and ensures price discovery and continuous liquidity for the token.
When the bonding curve accumulates 85 SOL total remaining token migrated to meteora.

- ### Dynamic Fee Structure :

Fees are calculated using a piecewise linear function based on user participation slots:
All fees are directed to the protocol's multisig wallet

### Please don't forget give ✨Star✨ and 🎞Fork🎞. 😊