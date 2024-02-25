# nextjs-web3modal-metamask-connect-24

This is a minimalistic project to show us how we can connect to metamask using web3modal in nextjs / react.

## Requirements

- git
- Nodejs & npm
- Yarn
- Metamask
- vscode

### Install git:

```bash
sudo apt install git-all
```

### Install nodejs & npm:

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install node
```

### Install yarn:

```bash
 npm install --global yarn
```

### Install vscode:

download and install the .deb package from the official Microsoft website, then run:

```bash
sudo apt install ./<file>.deb
```

## Creat next.js app

```bash
 yarn create next-app nextjs-web3modal-metamask-connect-24
```

## Run next.js app

```bash
yarn dev
```

ctrl + c stop server.

## Install ethers.js

```bash
yarn add ethers@^5.7.2
```

or uninstall

```bash
yarn remove ethers
```

## Install dependency

```bash
yarn add web3modal@^1.9.5
yarn add walletlink@^2.4.6
yarn add @walletconnect/web3-provider@^1.7.1
```

## Edit pages to realize project

I have deployed and approved SimpleStorage contract on sepolia for testing.

## Quickstart

Clone and install dependencies:

```bash
git clone https://github.com/lightrao/nextjs-web3modal-metamask-connect-24.git
cd nextjs-web3modal-metamask-connect-24
code .
yarn
```
