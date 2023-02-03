# Say Moo dot LOL 🐮

This is the repository for [Say Moo](https://saymoo.lol).

Contracts can be found in the [`contracts`](./contracts) directory, and the frontend in [`frontend`](./frontend).

## Getting Started

First, DM me at [@JoshCStein](https://twitter.com/JoshCStein) or [joshcs.lens](https://www.lensfrens.xyz/joshcs.lens) with your Ethereum wallet address to receive EMT tokens.

Then, you will need to connect your Ethereum wallet below to the Ethermint Sovereign Rollup to display the posts from the smart contract and post a "moo". You only need EMT to post -- sign in with your Ethereum wallet, switch to the chain of the rollup, and click "Load Moos" to see how many moos there have been before you decided to moo.

## Nice, what's going on under the hood?

Say Moo dot LOL is built with [Celestia](https://celestia.org), [RollKit](https://rollkit.dev), & [Ethermint](https://github.com/celestiaorg/ethermint).

Say Moo is a smart contract demo on a [sovereign rollup](https://celestia.org/glossary/sovereign-rollup) built on Celestia to provide [data availability](https://celestia.org/glossary/data-availability) and [consensus](https://ethereum.org/en/developers/docs/consensus-mechanisms), leveraging Ethermint with RollKit as the [execution environment](https://celestia.org/glossary/execution-environment).

This allows users to securely create and share Moos on the blockchain without the need for a centralized server or authority.

This application is deployed on IPFS and can be accessed through ENS ' target="_blank">([buildmarket.eth](https://buildmarket.eth.limo)) or [DNS](https://gmportal.xyz). Even the moo is on IPFS lol. Read more [here 🛸](https://mirror.xyz/joshcstein.eth/UbInedh4ToAAfsDklzSPb3R1_hVSHIdE97hvxIWYlOo)

## Developing this site yourself

```sh
# clone the repository
git clone https://github.com/jcstein/moo.git

# CD into directory, and frontend
cd moo/frontend

# Install dependencies
yarn

# Develop site locally
yarn dev
```

## Adding your contributions

This site was built with a mix of the [Ethermint with Rollkit tutorial](https://rollkit.dev/docs/tutorials/ethermint)
and [Celestia's Full Stack Modular Blockchain Development Guide](https://docs.celestia.org/developers/full-stack-modular-development-guide/).
The smart contract on this dapp was deployed with Foundry.

If you would like to contribute to this repository, please submit an
[issue](https://github.com/jcstein/moo/issues/new/choose) and
open a [pull request](https://github.com/jcstein/moo/compare)
with your changes for the issue.
