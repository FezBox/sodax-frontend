# Sodax SDK

The Sodax SDK provides a comprehensive interface for interacting with the Sodax protocol, enabling cross-chain swaps and money market operations.

## Installation

### NPM

Installing through npm:

`npm i --save @sodax/sdk`

### Local Installation

Package can be locally installed by following this steps:

1. Clone this repository to your local machine.
2. `cd` into repository folder location.
3. Execute `pnpm install` command in your CLI to install dependencies.
4. Execute `pnpm run build` to build the packages.
5. In your app repository `package.json` file, define dependency named `"@sodax/sdk"` under `"dependencies"`.
   Instead of version define absolute path to your SDK repository `"file:<sdk-repository-path>"` (e.g. `"file:/Users/dev/.../operation-liquidity-layer/packages/sdk"`).
   Full example: `"@sodax/sdk": "file:/Users/dev/operation-liquidity-layer/sdk-new/packages/sdk"`.

## Local Development

How to setup local development

1. Clone repository.
2. Make sure you have [Node.js](https://nodejs.org/en/download/package-manager) v18+ and corresponding npm installed on your system.
3. Execute `pnpm install` command (from root of the project) in your CLI to install dependencies.
4. Make code changes.
   1. Do not forget to export TS files in same folder `index.ts`.
   2. Always import files using `.js` postfix.

## Intent Solver Endpoints

Current Intent Solver API endpoints:
- **Production (mainnet)**: "TODO"
- **Staging** (mainnet): "https://staging-new-world.iconblockchain.xyz"

**Note** Staging endpoint contains features to be potentially released and is subject to frequent change!

## Relayer API Endpoints

Current Relayer API endpoints:
