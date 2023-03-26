# GnosisSwap

A one point destination to swap your cryptos on Gnosis blockchain.

### 📝 Project Description

#### 😎 Idea
- People put their money in banks thinking they have control over it, but in actuality, banks control the money.
- 'Your Money, Your Control,' is the core of Blockchain Technology which is how Decentralized Exchange work under the hood and this has long attracted me. As laws tighten, more people are turning to decentralized exchanges, discovering the actual value of blockchain and decentralized exchanges.
- Banks have unlimited control over money and can even refuse to enable customers to withdraw it in an emergency.
- There is no transparency in the operations of the Banks and everything is Centralized
- What's a better way to exchange your money while still having the ability to contribute to the Gnosis Ecosystem in the form of the fees which you anyhow have to pay to the big Institutions and banks.

#### 💻 Implementation
- We have forked UniswapV2 and deployed it on the Gnosis Network, as well as rendered our own UI and linked the smart contracts with the UI, allowing users to interact with the protocol.
- We have also made some modifications to the Uniswap's smart contracts to automatically transmit 0.01% of the total fees for the projects, 0.02% to the protocol for continued development and improvement of the protocol, and 0.3% to the liquidity providers for their contribution.
- Tools Used: Solidity, Remix, Gnosis(Chiado Testnet) Blockchain, uniswapV2, React and Metamask.

#### 👥 Intended Users
- People who wnat complete authority and transparency over their assets are the intended users as DEXs are decentralized and provides complete transparency and record which is publicaly avaliable to everyone on the Blockchain

### ✒ Summary
- GnosisSwap enables anyone from anywhere in the globe to purchase and sell cryptocurrencies immediately using Gnosis Network.
- GnosisSwap will contribute to the projects being build on the Gnosis Network by providing them with the funds as decided by the community.
- It does not discriminate anyone and will be open to everyone.
- Fan Token can be earned by providing liquidity and earning a steady passive income.


### 📺 Video Demo
[GnosisSwap Demo](https://ethglobal.com/showcase/hyperswap-wh66r)

### ☄️ What's next?
- More features will be introduced, such as farming, staking, and limit orders to make GnosisSwap more accessible to everyone and a common destination for everyone's needs.
- Creating a fully community-driven protocol in which the community votes on all protocol-related decisions.


### 💪 Deployed Smart Contract Addresses (Gnosis Chiado Testnet)
- Factory Contract: [0xe7f7067c9ecab27c5f7f13e02b13ed50931f6d0f](https://blockscout.com/gnosis/chiado/address/0xe7F7067C9ECAB27c5F7f13E02b13eD50931f6D0f)
- Router Contract: [0x90D4e9eB792602AA7A7506b477B878307C35e24A](https://blockscout.com/gnosis/chiado/address/0x90D4e9eB792602AA7A7506b477B878307C35e24A)
- WxDAI Contract: [0x0c0d088A6Fe7C65754D821eB94Bce29c2Cfb0D1d](https://blockscout.com/gnosis/chiado/address/0x90D4e9eB792602AA7A7506b477B878307C35e24A)
- Multicall Contract: [0x3221CE4Ade9a9564b34992a6d9Dd35E38D3884C9](https://blockscout.com/gnosis/chiado/address/0x3221CE4Ade9a9564b34992a6d9Dd35E38D3884C9)


### 🚫 License
This repository includes an MIT License statement.

### 💻 Deploying the GnosisSwap on local machine

Clone the repository

After cloning the repository, move into the UserInterface Directory

```sh
cd UserInterface
```

start the development server
```sh
yarn start

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```

