# Stake Wars: Episode III. Challenge 1

Create your Shardnet wallet & deploy the NEAR CLI.

## Useful links

Wallet:
>- [Wallet](https://wallet.shardnet.near.org/)

Explorer:
>- [Explorer](https://explorer.shardnet.near.org/)

Official documentation:
>- [Validator setup instructions](https://github.com/near/stakewars-iii)

join the official Discord:
>- https://discord.gg/XVsBbZGqUt

### Minimum Hardware Requirements
 - 4x CPUs; the faster clock speed the better
 - 8GB RAM
 - 500GB Disk
 - Permanent Internet connection (traffic will be minimal during testnet; 10Mbps will be plenty - for production at least 100Mbps is expected)


### Create Wallet
https://wallet.shardnet.near.org/

#### Setup NEAR-CLI

* Setup and Installation NEAR CLI
* View Validator Stats

## Update packages
```
sudo apt update && sudo apt upgrade -y
```
##### Install developer tools, Node.js, and npm
```
curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -  
sudo apt install build-essential nodejs
PATH="$PATH"
```
Check `Node.js` and `npm` version:
```
node -v
```
> v18.x.x

```
npm -v
```
> 8.x.x
##### Install NEAR-CLI
```
sudo npm install -g near-cli
```
