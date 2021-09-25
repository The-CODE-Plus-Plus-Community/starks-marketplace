
# INTRODUCTION
Many years have passed in apprehensions and concerns regarding the promising use cases for driving mainstream blockchain adoption. The year 2021 might spell a new chapter for the applications of blockchain technology with the rising popularity of NFTs. The sale of an NFT art collection by digital artist Beeple for $69 million set a completely new benchmark for NFTs.

![](https://miro.medium.com/max/1400/0*EBXqB5wJTWFeaT04.gif)
## NFT(Non-Fungible Token)
“Non-fungible” more or less means that it’s unique and can’t be replaced with something else. For example, a bitcoin is fungible — trade one for another bitcoin, and you’ll have exactly the same thing. A one-of-a-kind trading card, however, is non-fungible. If you traded it for a different card, you’d have something completely different.

## SPARKS MARKETPLACE

This project has been made by taking into consideration the use NFT in general market place to produce 
a safer and reliable chain of trusted users. One thing that has become apparent over the past few months is how quickly Ethereum scaling solutions like **Polygon**, **Arbitrum**, and **Optimism** are gaining momentum and adoption. These technologies enable developers to build the same applications they would directly on Ethereum with the added benefits of lower gas costs and faster transaction speeds among other things. Because of the value proposition that these solutions offer 
we are creating a safe marketplace for users to make their assets managable non tangible.

## Deployment

To deploy this project on your local system go step by step on your Windows Terminal in your preferred location

```bash
  npx create-next-app digital-marketplace
```
Next, change into the new directory and install the dependencies:
```bash
  cd digital-marketplace
```

```bash
  npm install ethers hardhat @nomiclabs/hardhat-waffle \
  ethereum-waffle chai @nomiclabs/hardhat-ethers \
  web3modal @openzeppelin/contracts ipfs-http-client \
  axios
```
Next, install the Tailwind dependencies:
```bash
  npm install -D tailwindcss@latest postcss@latest autoprefixer@latest
```

Next, initialize a new Hardhat development environment from the root of your project:
```bash
  npx hardhat

  ? What do you want to do? Create a sample project
  ? Hardhat project root: <Choose default path>
```
To run the test, run from your command line:
```bash
  npx hardhat test
```
To spin up a local network, open your terminal and run the following command, this should create a local network with 19 accounts.
```bash
  npx hardhat node
```
In a separate window, run the following command:
```bash
  npx hardhat run scripts/deploy.js --network localhost
```
To start the app, run the following command in your CLI:
```bash
  npm run dev 
```
## TECH STACK

1. Web application framework- **Next.js**
2. Faucet used to access the Faucet Network- **POLYGON**
3. Solidity development environment- **Hardhat**
4. File Storage- **IPFS**
5. Ethereum Web Client Library- **Ethers.js**
6. Authentication- **SAWO-API**
7. Api-Testing- **POSTMAN**

## TECH ELLABORATION

### NEXT.JS
<img src="https://raw.githubusercontent.com/andrebonna/serverless-next.js/HEAD/logo.gif" align="right" width="30%">
Next.js is the main framework for the **Frontend Development** in this project. The single page application which is made by the help of this framework allows the users to navigate through various sections of the marketplace i.e HOME, Selling Digital Asset, My assets and Creator-Dashboard. It provides a beautiful UI to handle their assets and navigate through their choice.

### POLYGON
<img src="https://c.tenor.com/kTRUwJEYLu8AAAAC/polygon-matic.gif" align="right" width="30%">
Polygon is a protocol and a framework for building and connecting Ethereum-compatible blockchain networks. Aggregating scalable solutions on Ethereum supporting a multi-chain Ethereum ecosystem. Polygon provides the core components and tools to join the new, borderless economy and society. With polygon, any project can easily spin-up a dedicated blockchain network which combines the best features of stand-alone blockchains (sovereignty, scalability and flexibility) and Ethereum (security, interoperability and developer experience). Additionally, these blockchains are compatible with all the existing Ethereum tools (Metamask, MyCrypto, Remix etc), and can exchange messages among themselves and with Ethereum. Polygon technology is materialized through two major components: Polygon framework and Polygon protocol.

### HARDHAT
<img src="https://hardhat.org/card.png" align="right" width="30%">
Easily deploy your contracts, run tests and debug Solidity code without dealing with live environments. Hardhat Network is a local Ethereum network designed for development.
Hardhat is the best choice for Solidity debugging. You get Solidity stack traces, console.log and explicit error messages when transactions fail.
Change anything you like. Even entire out-of-the-box tasks, or just parts of them. Flexible and customizable design, with little constraints.
Designed to make integrations easy, Hardhat allows you to keep using your existing tools while enabling deeper interoperability between them.

## IPFS
<img src="https://c.tenor.com/3HpVR4YO-IwAAAAM/ipfs-inter-planetary-file-system.gif" align="right" width="30%">
IPFS knows how to find that sweet, sweet aardvark information by its contents, not its location (more on that, which is called content addressing, below). The IPFS-ified version of the aardvark info is represented by that string of numbers in the middle of the URL (QmXo…), and instead of asking one of Wikipedia's computers for the page, your computer uses IPFS to ask lots of computers around the world to share the page with you. It can get your aardvark info from anyone who has it, not just Wikipedia.

And, when you use IPFS, you don't just download files from someone else — your computer also helps distribute them. When your friend a few blocks away needs the same Wikipedia page, they might be as likely to get it from you as they would from your neighbor or anyone else using IPFS.

IPFS makes this possible for not only web pages but also any kind of file a computer might store, whether it's a document, an email, or even a database record.

## ETHERS.JS
<img src="https://repository-images.githubusercontent.com/38885825/89e85900-78de-11ea-8040-98d5a598f2e6" align="right" width="30%">
The ethers.js library aims to be a complete and compact library for interacting with the Ethereum Blockchain and its ecosystem. It was originally designed for use with ethers.io and has since expanded into a more general-purpose library.

## SAWO-API
<img src="https://pbs.twimg.com/profile_images/1335871983188287496/Y_75bKdZ_400x400.jpg" align="right" width="30%">
Secure Authentication Without OTP or SAWO is the next thing in authentication, we wish to provide convenience both to developers and the users using the same platform by providing a one-tap authentication service that is secure, swift and sustainable. We have integrated to establish a trust based LOGIN system where users login to go into their accounts and navigate through the assets and trade on their purpose based products
  
