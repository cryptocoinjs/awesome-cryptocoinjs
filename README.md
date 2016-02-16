# Awesome CryptoCoinJS [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Useful crypto coins JavaScript libraries

*Mostly this list about __bitcoin__, but other crypto currencies are welcome!*

*Please put crypto name in brackets if library intended only for one crypto.*

*Please use specific category and alphabetical order.*

## List of content

  * [Main libraries](#main-libraries)
  * [BIPs](#bips)
  * [Wallets](#wallets)
  * [Blockchain explorers](#blockchain-exploreres)
  * [Full nodes](#full-nodes)
  * [P2P](#p2p)
  * [RPC](#rpc)
  * [Utilities](#utilities)
  * [Cryptography](#cryptography)

### Main Libraries

  * [bitcoin] [bcoin](https://github.com/indutny/bcoin)
  * [bitcoin] [bitcoinjs-lib](https://github.com/bitcoinjs/bitcoinjs-lib)
  * [bitcoin] [bitcore-lib](https://github.com/bitpay/bitcore-lib)

### BIPs

  * [bitcoin] [bip21](https://github.com/bitcoinjs/bip21)
  * [bitcoin] [bip38](https://github.com/bitcoinjs/bip38)
  * [bitcoin] [bip39](https://github.com/bitpay/bitcore-mnemonic) implementation for bitcore-lib
  * [bitcoin] [bip39](https://github.com/bitcoinjs/bip39)
  * [bitcoin] [bip66](https://github.com/bitcoinjs/bip66)
  * [bitcoin] [bip69](https://github.com/bitcoinjs/bip69)
  * [bitcoin] [bip70](https://github.com/bitpay/bitcore-payment-protocol)

### Wallets

  * [bitcoin] [copay](https://github.com/bitpay/copay) a multisignature wallet
  * [bitcoin] [cc-wallet-core](https://github.com/chromaway/cc-wallet-core) wallet with colored coin support
  * [bitcoin] [bitcore-wallet](https://github.com/bitpay/bitcore-wallet) a command line interface Multisig HD Wallet, based on bitcore-wallet-service

### Blockchain explorers

  * [bitcoin] [chromanode](https://github.com/chromaway/chromanode) blockchain explorer with colored coin support
  * [bitcoin] [insight-api](https://github.com/bitpay/insight-api) a bitcoin blockchain API for web wallets
  * [bitcoin] [insight-ui](https://github.com/bitpay/insight-ui)

### Full nodes

  * [bitcoin] [bitcore-node](https://github.com/bitpay/bitcore-node) full node with extended capabilities using Bitcore and Bitcoin Core
  * [bitcoin] [fullnode](https://github.com/ryanxcharles/fullnode) JavaScript implementation of Bitcoin

### P2P

  * [bitcoin] [bitcore-p2p](https://github.com/bitpay/bitcore-p2p) interface to the bitcoin P2P network for bitcore-lib
  * [bitcoin] [bitcore-p2p-cordova](https://github.com/getbitpocket/bitcore-p2p-cordova) interface to the bitcoin P2P network for Cordova/Phonegap apps
  * [bitcoin] [bitcoin-net](https://github.com/mappum/bitcoin-net) bitcoin networking that works in Node and the browser
  * [bitcoin] [bticoin-protocol](https://github.com/mappum/bitcoin-protocol) bitcoin network protocol streams

### RPC

  * [bitcoin] [bitcoin](https://github.com/freewil/node-bitcoin)
  * [bitcoin] [bitcoind-rpc](https://github.com/bitpay/bitcoind-rpc)
  * [bitcoin] [bitcoind-rpc-client](https://github.com/fanatid/bitcoind-rpc-client)
  * [bitcoin] [yajrpc](https://github.com/dcousens/yajrpc)

### Utilities

  * [*] [bitauth](https://github.com/bitpay/bitauth) authenticate with web services utilizing the same strategy as bitcoin
  * [bitcoin] [bitcoin-faucet-api](https://github.com/fanatid/bitcoin-faucet-api) bitcoin faucet service
  * [*] [bitcoin-proof](https://github.com/ethers/bitcoin-proof) merkle proof for a Bitcoin transaction
  * [*] [bitcoin-merkle-proof](https://github.com/mappum/bitcoin-merkle-proof) build and verify Bitcoin Merkle proofs (BIP37 supported!)
  * [bitcoin] [bitcoin-spv-utils](https://github.com/fanatid/bitcoin-spv-utils) useful functions for Simple Payment Verification
  * [bitcoin] [bitcoind-regtest](https://github.com/fanatid/bitcoind-regtest) run bitcoind in regtest mode for your own blockchain
  * [bitcoin] [bitcore-channel](https://github.com/bitpay/bitcore-channel) payment channels smart contract support for bitcore-lib
  * [bitcoin] [bitcore-message](https://github.com/bitpay/bitcore-message)
  * [bticoin] [bitcore-wallet-client](https://github.com/bitpay/bitcore-wallet-client) a client library for bitcore-wallet-service
  * [bitcoin] [bitcore-wallet-service](https://github.com/bitpay/bitcore-wallet-service) a multisig, HD wallet service (used by Copay)
  * [bitcoin] [bitcoinjs-message](https://github.com/bitcoinjs/bitcoinjs-message)
  * [bitcoin] [blkdat-stream](https://github.com/dcousens/blkdat-stream) ablk*.dat streaming module, useful for parsing the bitcoin blockchain
  * [bitcoin] [blockchainjs](https://github.com/chromaway/blockchainjs) bitcoin blockchain for wallets
  * [*] [bs58](https://github.com/cryptocoinjs/bs58) base58 encoding/decoding
  * [*] [bs58check](https://github.com/bitcoinjs/bs58check) a straight forward implementation of base58check extending upon bs58
  * [*] [coininfo](https://github.com/cryptocoinjs/coininfo) crypto currency specific information
  * [*] [coinkey](https://github.com/cryptocoinjs/coinkey) JavaScript component for private keys, public keys, and addresess for crypto currencies
  * [bitcoin] [coloredcoinjs-lib](https://github.com/chromaway/coloredcoinjs-lib) JavaScript Colored Coins library
  * [bitcoin] [stealth](https://github.com/cryptocoinjs/stealth) stealth addresses
  * [bitcoin] [wif](https://github.com/bitcoinjs/wif) bitcoin wallet import format JS encoding/decoding

### Cryptography

  * [*] [bitcore-ecies](https://github.com/bitpay/bitcore-ecies) a module for bitcore that implements the Elliptic Curve Integrated Encryption Scheme (ECIES)
  * [*] [drbg.js](https://github.com/fanatid/drbg.js) deterministic random bit generators from NIST SP 800-90A 
  * [*] [ecdsa](https://github.com/cryptocoinjs/ecdsa) JavaScript component to Eliptical Curve Cryptography signing and verify
  * [*] [ecurve](https://github.com/cryptocoinjs/ecurve) JavaScript component for Eliptical Curve Cryptography
  * [*] [elliptic](https://github.com/indutny/elliptic) fast Elliptic Curve Cryptography in plain JavaScript
  * [*] [pbkdf2-sha256](https://github.com/cryptocoinjs/pbkdf2-sha256) key derivation function primarily used for Scrypt 
  * [*] [secp256k1](https://github.com/cryptocoinjs/secp256k1-node) node.js bindings and pure JS implementation

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
