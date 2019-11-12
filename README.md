# Triton Electron GUI Wallet

### Introduction
XEQ is a private cryptocurrency based on Monero. Triton aims to release the first completely private ‘mint and burn’ stablecoin. Users will be able to burn our volatile coin Triton (XTRI), a fork of Monero, to mint a market equivalent amount of the Sao Dollar (SAO) – one USQD = $1 US. In turn, each SAO can be burned to mint $1 of XEQ.

More information on the project can be found on the [website](https://equilibria.network) and in the [whitepaper](https://cdn.discordapp.com/attachments/475870345010741269/561469142826483712/Triton_whitepaper_v3.1.pdf). Triton is an open source project, and we encourage contributions from anyone with something to offer. 
<p align="center">
 <img src="https://pbs.twimg.com/media/D2-ej8HU4AEB2l-.jpg" width="600">
</p>



### About this project

This is the new electron GUI for Triton. It is open source and completely free to use without restrictions, anyone may create an alternative implementation of the Triton Electron GUI that uses the protocol and network in a compatible manner.

Please submit any changes as pull requests to the development branch, all changes are assessed in the development branch before being merged to master, release tags are considered stable builds for the GUI.

#### Pre-requisites
- Download latest [Tritond](https://github.com/tritonnetwork/tritonprotocol/releases/latest)

#### Commands
```
nvm use 11.9.0
npm install -g quasar-cli
git clone https://github.com/tritonnetwork/triton-electron-wallet
cd triton-electron-wallet
cp path_to_triton_binaries/tritond bin/
cp path_to_triton_binaries/tritond-wallet-rpc bin/
npm install
quasar build -m electron -t mat
```
