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
 - 4-Core CPU with AVX support
 - 8GB RAM DDR4
 - 500GB Disk

### Create Wallet
https://wallet.shardnet.near.org/

#### Setup NEAR-CLI

* Setup and Installation NEAR CLI
* View Validator Stats

## Update packages
```
sudo apt update && sudo apt upgrade -y
```
## Install developer tools, Node.js, and npm
```
curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -  
sudo apt install build-essential nodejs
PATH="$PATH"
```
## Check `Node.js` and `npm` version:
```
node -v
```
> v18.x.x

```
npm -v
```
> 8.x.x
## Install NEAR-CLI
```
sudo npm install -g near-cli
```
## Validator Stats

Now that NEAR-CLI is installed, let's test out the CLI and use the following commands to interact with the blockchain as well as to view validator stats. There are three reports used to monitor validator status:


## Environment
The environment will need to be set each time a new shell is launched to select the correct network.

Networks:
- GuildNet
- TestNet
- MainNet
- **Shardnet** (this is the network we will use for Stake Wars)

Command:
```
export NEAR_ENV=shardnet
```

You can also run this command to set the Near testnet Environment persistent:
```
echo 'export NEAR_ENV=shardnet' >> ~/.bashrc
```
## NEAR CLI Commands Guide:

## Proposals
A proposal by a validator indicates they would like to enter the validator set, in order for a proposal to be accepted it must meet the minimum seat price.

Command:
```
near proposals
```

## Validators Current
This shows a list of active validators in the current epoch, the number of blocks produced, number of blocks expected, and online rate. Used to monitor if a validator is having issues.

Command:
```
near validators current
```

## Validators Next
This shows validators whose proposal was accepted one epoch ago, and that will enter the validator set in the next epoch.

Command:
```
near validators next
```

---


## [Setup and Run your Node](./challenge.md)

