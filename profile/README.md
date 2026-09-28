# Kastor Finance

Real-estate tokenization: investors pass KYC, buy fractions of a property with a dollar stablecoin and receive rental income in their wallet.

## On-chain

**BNB Smart Chain (mainnet), since 2022**

| Contract | Address |
|---|---|
| KastorToken (ERC-1155, one id per property) | [`0xA1394D580b5DB91128658E146a30154Ab01dF4CA`](https://bscscan.com/address/0xA1394D580b5DB91128658E146a30154Ab01dF4CA) |
| WhitelistVault (KYC) | [`0x38C9253F08d7b8313F6b6e641Ff7B022a725c31C`](https://bscscan.com/address/0x38C9253F08d7b8313F6b6e641Ff7B022a725c31C) |
| KastorEscrowV1 (primary sale) | [`0x44A39895859f9e12e81f802fD3Ea5cd5aa97DA4a`](https://bscscan.com/address/0x44A39895859f9e12e81f802fD3Ea5cd5aa97DA4a) |

**Stellar / Soroban (testnet), 2026**

[`kastor-soroban`](https://github.com/kastorfinance/kastor-soroban) is a Rust port of the contracts above: KYC registry, one SEP-41 token per property, escrowed primary sale and rental-income distribution. Testnet only, not audited.
