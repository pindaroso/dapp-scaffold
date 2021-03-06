# 🩸 Solana Dapp Scaffold

Bleeding edge scaffolding for Solana smart contract development

## Quickstart

```bash
git clone https://github.com/pindaroso/dapp-scaffold.git
cd dapp-scaffold
```

Install dependencies and run the development server.

```bash
yarn
yarn dev
```

Build and run Anchor with a local Solana validator

```bash
anchor test --detach
```

## Environment Setup

1. Install [Rust](https://rustup.rs)
2. Install [Solana](https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool)
3. Install [Node](https://nodejs.org/en/), [NPM](https://www.npmjs.com/) and [Yarn](https://yarnpkg.com/)
4. Install [Anchor](https://github.com/project-serum/anchor)

## Directory structure

### `app`

Front end code for UI which pulls in IDL from Anchor.

### `programs`

Contract code to be deployed on Solana.

## Is this better than [solana-labs/dapp-scaffold](https://github.com/solana-labs/dapp-scaffold)?

No. It might actually be worse. This scaffolding adds the following:

* [Anchor](https://github.com/project-serum/anchor)
* [Goki Wallet Adapter](https://walletkit.goki.so/)
* [NextJS](https://nextjs.org/)
