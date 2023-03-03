<div align="center" >
  <h1>Padawan Wallet</h1>
  <br/>
  <br/>
  <img src="./images/logo.png" alt="Logo 1.0.0" width="400">
</div>
<br/>
<br/>

[![GitHub](https://img.shields.io/github/license/thunderbiscuit/padawan-wallet?color=brightgreen)](https://github.com/thunderbiscuit/padawan-wallet/blob/master/LICENSE) 
![Kotlin Version](https://img.shields.io/badge/kotlin-v1.8.0-orange) 
[![Conventional Commits](https://img.shields.io/badge/conventional%20commits-1.0.0-yellow.svg)](https://conventionalcommits.org) 
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/thunderbiscuit/padawan-wallet)](https://github.com/thunderbiscuit/padawan-wallet/releases)
[![Twitter](https://img.shields.io/badge/twitter-%40padawanwallet-b8bb26)](https://twitter.com/padawanwallet)

A testnet-only bitcoin wallet full of tutorials on how to use bitcoin wallets.

We're building the app you'll want to recommend to your teenage cousins at Christmas or to your dad that keeps asking questions about bitcoin. Padawan aims to be a self-study tool, getting its users acquainted with the usual workflow and basic jargon of mobile wallets in a risk-free environment perfect for experimentation and learning (testnet).

We think testnet is an underused resource outside of software development circles, and believe it can be leveraged for bitcoin-curious people everywhere. Testnet offers all the complexity of mainnet, and one of the goal of this wallet is to eventually foray into these more advanced bitcoin features (output descriptors, multisig wallets, DLCs) and offer a training and testing ground for users.
<br/>

## Download
You can download the latest apk for this app on the [`v0.10.0: Junior Jabba` release page](https://github.com/thunderbiscuit/padawan-wallet/releases/tag/v0.10.0) or find it on the [Google Play Store](https://play.google.com/store/apps/details?id=com.goldenraven.padawanwallet).
<br/>

## Screenshots
<div align="center">
  <img src="./images/screenshots.jpg" alt="" width="900">
</div>
<br />

## FAQ
### Tutorials you say?
The tutorials in the app are called _Chapters_, and there are currently 9 of them:

1. What is the Bitcoin testnet?  
2. Receiving bitcoin
3. Sending bitcoin
4. What is the mempool?
5. What are transaction fees?
6. Bitcoin units
7. What is a recovery phrase?
8. Recovering your wallet
9. The different types of wallets

### Where can I get testnet coins?
There are many bitcoin testnet faucets out there, but Padawan uses native segwit addresses uniquely (bech32), so you'll need a faucet that can send to those. We suggest these two:

1. https://coinfaucet.eu/en/btc-testnet/
2. https://bitcoinfaucet.uo1.net/

### How can I delete my wallet?
You cannot delete your wallet directly from within the app. This is on purpose, to make sure people don't delete wallets without putting in some work. If you are certain that your wallet is empty (if it's not, send the testnet coins back to us!), you can delete the wallet by clearing all app data for Padawan in your Android settings, or you can uninstall and reinstall the app directly from the Play Store. 

### Building and running Padawan
To build and run the app from source, you'll need:
- Android Studio
- A phone with Android 8 OS or above (Android Oreo, API level 26) with USB debugging activated OR an emulator on your development machine

### How can I contribute?
If you think this project is interesting and would like to contribute or simply provide feedback and bounce ideas, open an issue on this repository, or message the [@padawanwallet](https://twitter.com/padawanwallet) Twitter account!
