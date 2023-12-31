# Arthera Hardhat Template

This Hardhat template is ideal for hackathons and quick prototyping.

It includes:

-   [Typescript](https://www.typescriptlang.org/)
-   [Ethers v6](https://docs.ethers.org/v6/)
-   [Open Zeppelin contracts](https://www.openzeppelin.com/contracts)
-   [Hardhat Verify plugin](https://hardhat.org/hardhat-runner/plugins/nomicfoundation-hardhat-verify)

You may want to check the [dev resources](https://docs.arthera.net/build/developing-sc/dev-resources) available in Arthera docs, and [this walkthrough video](https://www.youtube.com/watch?v=kjPvFk4qmpc). 

## Supported networks

-   [Goerli](https://goerli.etherscan.io/)
-   [Arthera Testnet](https://explorer-test.arthera.net/)

## Install

```
pnpm install
```

Create a `.env` file:

```
cp .env.template .env
```

Add your own keys in the `.env` file.

## Test

```
pnpm test
```

## Deploy

Deploy to Goerli:

```
pnpm deploy:goerli
```

Deploy to Arthera Testnet:

```
pnpm deploy:arthera
```

## Mint

On Goerli:

```
pnpm mint:goerli 42
```

On Arthera Testnet:

```
pnpm mint:arthera 42
```

## Send

On Goerli:

```
pnpm send:goerli 8
```

On Arthera Testnet:

```
pnpm send:arthera 8
```

## Versions

-   Node [v18.17.1](https://nodejs.org/uk/blog/release/v18.17.1/)
-   PNPM [v8.7.5](https://pnpm.io/pnpm-vs-npm)
-   Hardhat [v2.17.2](https://github.com/NomicFoundation/hardhat/releases/tag/hardhat%402.17.2)
-   OpenZeppelin Contracts [v4.9.3](https://github.com/OpenZeppelin/openzeppelin-contracts/releases/tag/v4.9.3)
-   Ethers [v6](https://docs.ethers.org/v6/)

## Support

You can contact me via [Element](https://matrix.to/#/@julienbrg:matrix.org), [Telegram](https://t.me/julienbrg), [Twitter](https://twitter.com/julienbrg), [Discord](https://discordapp.com/users/julienbrg), or [LinkedIn](https://www.linkedin.com/in/julienberanger/).
