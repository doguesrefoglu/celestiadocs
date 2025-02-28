# Optimint

![optimint](/img/optimint.png)

[Optimint](https://github.com/celestiaorg/optimint) is an Optimistic-Rollup
implementation of ABCI (Application Blockchain Interface) in
order to build sovereign chains using the Cosmos-SDK for Celestia.

It is built by replacing Tendermint, the Cosmos-SDK
consensus layer, with a drop-in replacement that
communicates directly with Celestia's Data Availability layer.

It spins up an optimistic rollup, which collects transactions into blocks and
posts them onto Celestia for consensus and data availability.

The goal of Optimint is to enable anyone to design and deploy a Cosmos Zone
on Celestia in minutes.

## Tutorials

The following tutorials will help you get started building
Cosmos-SDK applications that connect to Celestia's Data Availability
Layer via Optimint. We call those chains Sovereign Rollups.

You can get started with the following tutorials:

- [Wordle Game](./wordle.md)
- [CosmWasm Tutorial](./cosmwasm.md)
