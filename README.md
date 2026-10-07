# Thomas Wallet — Bitcoin Testnet Starter

This is a phone-friendly development starter, not a production cryptocurrency wallet.

## Current status
- Testnet-only UI
- Wallet onboarding
- Demo recovery screen
- Demo dashboard
- Security requirements documented
- No real private keys
- No real Bitcoin
- No real transaction signing

## Next cryptographic implementation
Use audited, maintained Bitcoin libraries to implement:
1. BIP-39 mnemonic generation using the platform CSPRNG.
2. BIP-32/84 key derivation for native SegWit testnet addresses.
3. Encrypted local key storage.
4. Testnet transaction construction and signing.
5. Fee estimation and UTXO selection.
6. Address validation and checksum verification.
7. Recovery tests using known test vectors.

Do not deploy this starter as a real-money wallet.
