<h1 align="center">🦊 STARKS MARKET PLACE</h1>

## INTRODUCTION
Many years have passed in apprehensions and concerns regarding the promising use cases for driving mainstream blockchain adoption. The year 2021 might spell a new chapter for the applications of blockchain technology with the rising popularity of NFTs. The sale of an NFT art collection by digital artist Beeple for $69 million set a completely new benchmark for NFTs.

![](https://miro.medium.com/max/1400/0*EBXqB5wJTWFeaT04.gif)
## NFT(Non-Fungible Token)
“Non-fungible” more or less means that it’s unique and can’t be replaced with something else. For example, a bitcoin is fungible — trade one for another bitcoin, and you’ll have exactly the same thing. A one-of-a-kind trading card, however, is non-fungible. If you traded it for a different card, you’d have something completely different.

## STARKS MARKETPLACE

This project has been made by taking into consideration the use NFT in general market place to produce 
a safer and reliable chain of trusted users. One thing that has become apparent over the past few months is how quickly Ethereum scaling solutions like **Polygon**, **Arbitrum**, and **Optimism** are gaining momentum and adoption. These technologies enable developers to build the same applications they would directly on Ethereum with the added benefits of lower gas costs and faster transaction speeds among other things. Because of the value proposition that these solutions offer 
we are creating a safe marketplace for users to make their assets managable non tangible.

## TECH STACK

1. Web application framework- **Next.js**
2. Solidity development environment- **Hardhat**
3. File Storage- **IPFS**
4. Ethereum Web Client Library- **Ethers.js**


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

  
