# Solana Bootcamp Final Project
## Solty Dogs Dogbone NFT

Solty Dogs is a (fictional) Solana based game where Dogbone NFTs are collected.

A Dogbone NFT is defined by is primary_color, accent_color, rarity, and short_description properties.

### Build & Deploy
- `cd program`
- `cargo build-sbf`
- `solana config set --url devnet`
- contract deployment requires Solana, so get some. `solana airdrop 1`
- verify you have enough Solana to cover fees `solana balance`
- `solana program deploy target/deploy/nft.so`

### Operations
- Mint: Create new Dogbone NFT based on primary color, accent color, rarity and description inputs.
- Transfer: Send Dogbone NFT between accounts.
- Burn: Remove Dogbone NFT from circulation
