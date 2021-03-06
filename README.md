# EBWallet



It is **not** production code and should be used for educational puproses only.

## Installation

```
git clone https://github.com/gandhichintan/electron-blockchain-wallet.git
cd jswallet
npm install
npm start
```

## Design Principles

Key derivation is the beating heart of a Bitcoin Wallet and most security concerns have to do with this first step.

My code is mainly intended as an illustration of the following pattern:

![Key Derivation](https://github.com/gandhichintan/electron-blockchain-wallet/blob/master/assets/Key%20Chain.png)

## Building

This project was built using [electron-forge](https://github.com/electron-userland/electron-forge). I have had problems building it in some machines and apparently the [issue is not uncommon](https://github.com/electron-userland/electron-forge/issues/434). In theory it should work like so...

```
npm publish
```

## Warnings

As stated above this is **not** production code. 
It is set to work with *testnet* by default but by a simple change in the `env.js` it could well function with real bitcoins!


## Moving Forward

If anyone outhere has any coold suggestions on developing this pet project further please submit ideas in the issues tab.
