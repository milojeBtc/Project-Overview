# <i>Blockchain Projects on Bitcoin, EVM(Ethereum, Binance, Avalanche, Polygon, Aurora) and Solana.</i>

I have successfully developed multiple NFT/Blockchain projects encompassing various features such as minting, staking, evolution/breeding, raffle/auction houses, Launchpad, Marketplace, and P2E games including dice, crash, jackpot, coinflip, among others. All repositories are currently set to private status.

<h2 align="center"><u><strong><i>฿itcoin Projects</i></strong></u></h2>

<h3><u><strong><i>Bitcoin Defi</i></u></h3>
<hr />
  
![Blockchain](https://img.shields.io/badge/Blockchain-121D33?style=flat-square&logo=blockchain.com&logoColor=white)
![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=flat-square&logo=bitcoin&logoColor=white)
![Web3](https://img.shields.io/badge/Web3-E2761B?style=flat-square&logo=web3&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-f7f7f7?style=flastic&logo=Next.js&logoColor=000000)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white)
![DeFi](https://img.shields.io/badge/DeFi-00b0ff?style=flat-square&logo=ethereum&logoColor=white)
![Automated Market Making](https://img.shields.io/badge/Automated%20Market%20Making-1C1C1C?style=flat-square)
![MongoDB](https://img.shields.io/badge/MongoDB-F7F7F7?style=flat-square&logo=mongodb&logoColor=49A248)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

ArcusLab is a cutting-edge Bitcoin decentralized finance (DeFi) platform that enables users to access Faucet BRC20 tokens, as well as supply or borrow BTC and BRC20 tokens with an over-collateral ratio. Our platform utilizes Next.js for the frontend, Node.js for the backend, and MongoDB for the database. Additionally, we leverage Deep Lake API, DLC, Oracle, and Crypto Finance API for liquidation and automated market-making (AMM) processes. The alpha version of our platform will soon be released on the testnet. Presently, users can interact with our platform using the Unisat Wallet, with plans to integrate XVerse and Leader Wallet in the future.
<img align="right" width="300px" src="https://i.ibb.co/B3YM82w/Arcuslab.png" alt="Arcuslab" border="0" >

- Live: <a href="https://arcusbtc.com/">ArcusLab</a>
- Github repos: 
  - backend repo: <a href="https://github.com/milojeBtc/arcus-app">ArcusLab-Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/ArcusLab-FE">ArcusLab-Frontend</a>
  
<h3><u><strong><i>Ordinal Swap MarketPlace</i></strong></u></h3>
<hr />
Munchswap is bitcoin ordinal multi swap platform. Users can swap ordinals with their ordinals or buy use BTC. I used Next.js for Frontend and Nest.js for backend, PostgreSQL for Database, Docker for Devops. For Generate Swap PSBT, I used bitcoinJs lib and UTXO. Now it's live in bitcoin mainnet. Users can use Unisat, XVerse and Leader wallets for use this platform.
<img align="right" width="300px" src="https://i.ibb.co/0Z4NMzP/Munch.png" alt="Munch" border="0" />

- Live: <a href="https://munchswap.xyz/">MunchSwap</a>
- Github repos: 
  - backend repo: <a href="https://github.com/milojeBtc/swap-apis">MunchSwap-Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/munchswap/">MunchSwap-Frontend</a>


<h3><u><strong><i>BRC20 Airdrop</i></strong></u></h3>
<hr />

This is a BRC20 token Airdrop project on Bitcoin network. Bitmap ordinal owners can airdrop BRC20 tokens to taproot address.
<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/453817f2-3920-4626-9c53-1041e67f15b5">

BmpBrc is a BRC20 airdrop platform in Bitcoin Network. I get user's taproot address and check user is bitmap ordinal owner or not. Integrate Unisat, Leader, XVerse wallets in Frontend and used PSBT, bitcoinjs lib for deploy, mint and send BRC20 tokens to user's taproot address. Get familiar with Ordinal technology(like utxo, psbt, inscribe), I can make the Bitcoin Defi project use Orinal or BRC20 tokens.
- Live: <a href="https://bmpbrc.com/">BMP BRC20</a>
- Github repos: 
  - backend repo: <a href="https://github.com/milojeBtc/BRC20-withdraw-Backend">BRC20-Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/BRC20-Withdraw-Unisat">BRC20-Frontend</a>


<h3><u><strong><i>UnderWorld Lending</i></strong></u></h3>
<hr />

This is a Ordinal Lending project on Bitcoin network. Users can borrow money use their Bitcoin Ordinals or swap their Ordinals to BTC.

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/335f566b-a90d-4997-b2fa-bd318b484830">

UnderWorldLending Platform is an BTC Lending Platform so users can borrow BTC use their BTC Ordinals or Swap Ordinals with BTC. The main purpose of this platform is to facilitate liquidity for borrowers who urgently need it or require it at a specific time. Additionally, we aim to help lenders earn money through this process. Everything is 100% secure, and it will be done through the BTC blockchain. Everything will be transparent. Borrowers won't have to send your ordinal anywhere during borrow money period. With the help of Deep Lake, DLCs (Discreet Log Contracts) and PSBT (Partially Signed Bitcoin Transactions) for Ordinals.

- Live: <a href="https://degens.fi/">UnderWorldLending</a>
- Github repos: 
  - backend repo: <a href="https://github.com/milojeBtc/BTC-NFT-Lending-BE">UnderWorldLending-Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/BTC-NFT-Lending">UnderWorldLending-Frontend</a>


<h3><u><strong><i>Ordinal Raffle</i></strong></u></h3>
<hr />
Users can participate in Ordinal Raffle by sending 1000 PSAT per ticket to “Deposit Address”.
If counter down starts and user is winner, he will get the inscription, but if he is a loser, he lost all, and can't be refunded.

I developed this project front end with React, and the backend with Node.js.

<img align="right" width="300px" src="https://github.com/FeloniousGru-Super/projects/assets/92280175/231f9b82-8281-43ae-af54-e7e8f1ed5035">

- Site: <a href="https://satoshipunks.art">SatoshiPunks</a>
- Github repos: 
  - backend repo: <a href="https://github.com/FeloniousGru-Super/ordipucks-be">SatoshiPunks-Backend</a>
  - frontend repo: <a href="https://github.com/FeloniousGru-Super/ordipunks-fe">SatoshiPunks-Frontend</a>

<br />


<h3><u><strong><i>Arcus Lab (Lending & Borrow BRC-20 and BTC)</i></strong></u></h3>
<hr />
Transform your BRC-20 into a dynamic asset with Arcus. Lend your Bitcoin or ORDI, or other BRC-20 tokens and earn competitive yields through our automated rate algorithms. Simple, secure, and lucrative – a smarter way to grow your Bitcoin holdings.
<br />
Borrow against your BTC Assets with ease. Arcus offers low-interest loans with flexible repayment, secured by BTC or BRC-20 tokens. Select your collateral, decide on the loan amount, you're always in control.
<br />
Platform pay for user's gas fee, so users won't use any their fund for gas.
<br />
<strong>And I implemented one click loan by sign multi-signed psbt on the user's end.</strong>
<br />
<br />
<img align="right" width="300px" src="https://github.com/FeloniousGru-Super/projects/assets/92280175/165319b6-7bbd-40de-b768-5eaf3b3868e6">

Front End: React + Typescript + Material UI
<br />
Back End: Node.js + Typescript + Bitcoinjs-Lib + MongoDB

- Site: <a href="https://arcusbtc.com">Arcus Lab</a>
- Github repos: 
  - backend repo: <a href="https://github.com/FeloniousGru-Super/Arcus-BE">Arcus Backend</a>
  - frontend repo: <a href="https://github.com/FeloniousGru-Super/Arcus-FE">Arcus Frontend</a>
<br />


<h3><u><strong><i>OrdVision (Multi Swap Ordinals with BTC)</i></strong></u></h3>
<hr />
OrdVision stands out as a sophisticated platform designed to facilitate the exchange of Bitcoin ordinals. It offers users the flexibility to swap their ordinals or to purchase using BTC. Below are some key components that make up the OrdVision ecosystem:
<br />

- Frontend Development: The interface is powered by Next.js, ensuring a seamless and dynamic user experience.
- Backend Services: The backend functionality is handled by Nest.js, providing a robust framework for server-side operations.
- Database Management: PostgreSQL is utilized for its reliable and scalable database solutions.
- DevOps: Docker streamlines the development process, allowing for efficient containerization and deployment.
<br />
For the critical feature of generating Swap Partially Signed Bitcoin Transactions (PSBTs), OrdVision leverages the capabilities of the bitcoinJs library alongside Unspent Transaction Outputs (UTXOs).
<br />
As the platform reaches its operational phase on the Bitcoin mainnet, it retains simplicity in terms of accessibility. Users have the convenience of engaging with the platform using various wallets including:
<br />
<img align="right" width="300px" src="https://github.com/FeloniousGru-Super/projects/assets/92280175/da4da8e1-70d0-4284-b030-bae783ac3a0e">

- Unisat
- XVerse
- Leader Wallet
<br />


- Site: <a href="https://ordvision.io">OrdVision</a>

<br />

<h2 align="center"><u><strong><i>Bitcoin Projects</i></strong></u></h2>
### Multi-chain (Bitcoin, Etheruem, Binance, Solana)

<h3><u><strong><i>Playzelo</i></strong></u></h3>
<hr />

This is a game project deployed on blockchain networks. Users can play games use crypto

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/80a7c5b9-674d-4db5-ba0f-35e9befc888b">


Playzelo is a game project deployed on blockchain networks. There are several games like (Scissors, Turtlerace, Mines, Idce, Plinko, Slot, Crash). Users can play game use native tokens and USDT, USDC tokens on bitcoin, ethereum, solana, binance.

- Live: <a href="https://playzelo.xyz/">Playzelo</a>
- Github repos: 
  - backend repo: <a href="https://github.com/milojeBtc/scissors/tree/master/backend">Playzelo Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/scissors/tree/master/frontend">Playzelo-Frontend</a>
  - admin repo: <a href="https://github.com/milojeBtc/scissors/tree/master/admin">Playzelo-Admin</a>

<h2 align="center"><u><strong><i>Solana</i></strong></u></h2>

<h3><u><strong><i>Hydra Swap</i></strong></u></h3>
<hr />

This is a Defi project on Solana network. Trade, earn, and grow with HydraSwap’s intelligent cross-chain DEX featuring concentrated liquidity on the high-performance Solana blockchain.

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/78a3d3a7-da63-4cd5-a011-de5c40ffe54c">

HydraSwap is a next-generation cross-chain DEX powered by our exclusive Hydra Market Maker (HMM) smart pricing algorithm. It helps liquidity providers (LPs) enhance their returns up to 4x and improves their impermanent loss profile. HydraSwap integrates smarter pricing with concentrated liquidity to create greater capital efficiency and superior earnings for LPs.HydraSwap’s proprietary features combined with the speed and convenience of Solana, deliver a fast and reliable DEX. By addressing the needs of LPs we aim to create a robust trading venue with deep liquidity for DeFi.

- Live: <a href="https://hydraswap.io/">HydraSwap</a>
- Github repos: 
  - backend repo: <a href="https://github.com/milojeBtc/hydra-Defi-BE">Hydra-Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/hydra-Defi-FE">Hydra-Frontend</a>
  - SmartContract repo: <a href="https://github.com/milojeBtc/hydra-Defi-SC">Hydra-SmartContract</a>



<h3><u><strong><i>SeekSyndicate</i></strong></u></h3>
<hr />

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/c8fdcde4-fcca-4f49-b026-a30a93fb635f">

This is one kind of P2E game. Users can get reward while playing Game.

Build Smart Contract use Anchor(Rust) and Frontend use Next.js. NFT Holders can faucet SPL Token(SEEK) as Reward.

- Live: <a href="https://www.seekersyndicate.com/">Seek Syndicate</a>
- Github repos: 
  - smart contract repo: <a href="https://github.com/milojeBtc/SPLFaucetSmartContract">Seek Syndicate Smart Contract</a>
  - frontend repo: <a href="https://github.com/milojeBtc/SOLFaucetFE">Seek Syndicate Front End</a>


<h3><u><strong><i>Hubble Protocol</i></strong></u></h3>
<hr />

Hubble is a decentralized finance (DeFi) protocol built on the Solana blockchain. Hubble enables you to borrow USDH against multiple assets. Borrowing USDH allows users to access the liquidity (cash on hand) in their long-term holding tokens.

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/801609f5-216b-4792-9db8-c1140ac38e64">

- Live Link: <a href="https://hubbleprotocol.io">Hubble Protocol</a>
  - Functionality
    - Lets users borrow USDH for a one-time 0.5% fee and low interest rates. With the interest yield on deposits, your collateral value can grow to negate fees.
    - Developed governance and utility Token(HBB) and over-collateralized stablecoin(USDH).
    - Hubble’s capital-efficient 110% collateral ratio lets users leverage up to 11x on their deposits.
- Github repo:
  - Contract: <a href="https://github.com/milojeBtc/Hubble-Backend">Hubble Smart Contract</a>
  - Frontend: <a href="https://github.com/milojeBtc/Hubble-FrontEnd">Hubble Frontend</a>
  - Frontend: <a href="https://github.com/milojeBtc/Hubble-landing-page">Hubble Landing Page</a>

<h2 align="center"><u><strong><i>Ethereum</i></strong></u></h2>

<h3><u><strong><i>DigiMonkz</i></strong></u></h3>
<hr />

This is a NFT project on Etheruem blockchain. Users can mint GEN111 or GEN2 NFTs and can get artifact as a reward from Staking.

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/7bfef799-1101-47a0-b747-bcb910683e92">

DigiMonkz is the leading Web3 Wellness NFT collection that is building alongside other passionate and accomplished entrepreneurs as we enter a Digital Age of unprecedented mental health problems. DigiMonkz fill a HUGE NEED as it provides premium content and instruction to LEVEL UP your mind, body, and spirit. We are designed for the NEXT GENERATION of Digital Entrepreneurs and Web3 Fans. The Life of a Degen Journey, as Bebe calls the DigiMonkz Mastermind, is designed to bring more balance and power to the lives of Web3 Degens.

- Live: <a href="https://digimonkz.com/">Digimonkz</a>
- Github repos: 
  - smart contract repo: <a href="https://github.com/milojeBtc/DigiMonkz-Staking">Digimonkz-SmartContract</a>
  - frontend repo: <a href="https://github.com/milojeBtc/DigiMokz-Frontend">Digimonkz-Frontend</a>
  

<h3><u><strong><i>MetaSeep Protocol</i></strong></u></h3>
<hr />

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/6f81e434-a42c-4cd5-9524-6b1568232ff3">

A kind of NFT & ETH Raffle project. Users enter raffle and buy tickets on Etheruem network. They can get Eth or NFT for reward when they win Raffle.

- Demo: <a href="https://metasweep.io/">MetaSweep Protocol</a>
- Live: <a href="https://metawin.com">MetaWin Protocol</a>
- Github repos: 
  - smart contract repo: <a href="https://github.com/milojeBtc/RaffleSmartContract">MetaSweep Smart Contract</a>
  - backend repo: <a href="https://github.com/milojeBtc/RaffleBackend">MetaSweep Backend</a>
  - frontend repo: <a href="https://github.com/milojeBtc/RaffleProject">MetaSweep Front End</a>

<h2 align="center"><u><strong><i>Avalanche</i></strong></u></h2>

<h3><u><strong><i>Plunder The Void Mint Site</i></strong></u></h3>
<hr />

This is mint website on avalanche network. I used Solidity(ERC 721) to write smart contract and Node/Express, MongoDB to make leaderboard page, and Next.js in front-end side. Mint supply is 500 NFTs.

<img align="right" width="300px" src="https://user-images.githubusercontent.com/89365150/209906661-40d7a303-d0ae-4bf8-a3ca-b159927d72ab.png">

- Demo: <a href="https://avalanche-nft-mint.vercel.app">Plunder The Void</a>
- Live: <a href="https://plunderthevoid.io">Plunder The Void</a>
  - Functionality
    - 500 NFTs
    - Mint price is 100 USDC
    - Need to put discord Name or Id
    - Avalanche network
- Testnet deployed contract address: <a href="https://testnet.snowtrace.io/address/0x80EEE1615feeD9c03aEbe94dCA6aDF1680cd41C6#code">Testnet contract</a>
- Mainnet deployed contract address: <a href="">Mainnet contract</a>
- Github repo:
  - Contract: <a href="https://github.com/milojeBtc/dale-mint-contract-avax">dale-mint-contract-avax</a>
  - Backend: <a href="https://github.com/milojeBtc/dale-mint-backend-avax">dale-mint-backend-avax</a>
  - Frontend: <a href="https://github.com/milojeBtc/dale-mint-frontend-avax">dale-mint-frontend-avax</a>

<h2 align="center"><u><strong><i>Binance</i></strong></u></h2>

<h3><u><strong><i>CashCow Protocol</i></strong></u></h3>
<hr />

<img align="right" width="300px" src="https://github.com/milojeBtc/Blockchain-Projects-Overview/assets/89193350/72111c4e-8b74-4779-b778-aeafcd58f904">

Cashcow is an innovative decentralized platform that combines Non-Fungible Tokens (NFT) and Fungible Tokens (FT). It is a futuristic NFT project that utilizes cutting-edge Defi tools to maximize returns. ShoeFy can amplify the NFTs potential by including both farming and staking to generate passive income.

- Live: <a href="https://cashcowprotocol.com">CashCow Protocol</a>
  - Functionality
    - Established DeFi platform where users can earn profit from mining, reselling, trading, staking, farming, and the LP program 
    - Closely collaborated with the product and developer teams to improve the efficiency of the platform
    - Introduced Sub-graph third party to reduce the weight of web3 calls and improve web-app speed 46%
- Github repo:
  - Contract: <a href="https://github.com/milojeBtc/CashCowBackEnd-Solidity-">Cashcow Smart Contract</a>
  - Frontend: <a href="https://github.com/milojeBtc/CashCowFrontEnd">Cashcow Frontend</a>

<h2 align="center"><u><strong><i>Binance Smart Chain</i></strong></u></h2>

<h3><u><strong><i>BNBPot (Decentralized Casino)</i></strong></u></h3>
<hr />
Worlds first truly decentralized casino. BNBPot is simply a web3 application that visualize the events & activities of smart contracts on blockchains
<br />
No account & no deposit | Fully on-chain game code | Guaranteed instant payouts | Direct player vs. player | No censorship
<br />
Implemented NFT Auction at first for room-ownership of each games.
<br />
<img align="right" width="300px" src="https://github.com/FeloniousGru-Super/projects/assets/92280175/cb018f73-5c18-40db-854c-5d4b2701d8bb">

- Frontend Development: React | Tailwind CSS | Typescript | SEO | Web3.js
- Backend Services: Node.js | Typescript | Web3.js
- Database Management: PostgreSQL
- DevOps: Digital Ocean | CI/CD
<br />

- Site: <a href="https://bnbpot.io">BNBPot</a>

<br />

<h3><u><strong><i>Crypto Legions (P2E NFT Game)</i></strong></u></h3>
<hr />
Cutting edge Play-To-Earn NFT game on the BSC network
<br />
<img align="right" width="300px" src="https://github.com/FeloniousGru-Super/projects/assets/92280175/83da6aff-b22c-4250-aae4-7846790dcbf9">

- The Features
  - Minting
  - Hunting
  - Buying and Selling on NFT Marketplace
  - Smart Claim System
  - Reincarnation

- The Challenge
  - Faced the secret problem - Random Number Generation in the smart contract.
  - By using Chainlink, made the perfect Random Number in the smart contract and protected the attacks from hackers.

- The Problem
  - Play-To-Earn NFT games typically fail when their economies become unsustainable. This usually happens when established players hoard ever-lasting NFTs, and start withdrawing rewards in bulk without contributing anything back. Without enough new players joining, the economy stagnates: All the rewards have been eaten up by whales, with little incentives left for everybody else. This is when game creators tend to panic and impose knee-jerk measures that catch remaining players off guard, damaging trust and making a bad situation worse.

- The Solution
  - Crypto Legions has invented a 'Play Forever Earn Forever' system, consisting of a combination of innovative updates including our Transparent Economy Status, our Smart Claim System™, our proven Omni-Balanced Oracle™ System, our Reserve Pool™, and our Reincarnation™ process. The combination of these features allows players to keep playing forever and to give birth to a new token, whenever needed and voted by the players who are taking the decision to Reincarnate based on the transparently provided data of the economy status. To fully understand the power of this system, you need to go over all the features in detail in this whitepaper.

<br />

- Frontend Development: React | Material UI | Tailwind CSS | Typescript | SEO | Web3.js
- Backend Services: Node.js | Typescript | Web3.js
- Third Party: Subgraph
- Database Management: MongoDB
- DevOps: AWS | CI/CD
<br />

- Site: <a href="https://cryptolegions.app/">Crypto Legions</a>
- Github repos: 
  - backend repo: <a href="https://github.com/Crypto-Legions/CryptoGamesAgency-Backend">Backend</a>
  - frontend repo: <a href="https://github.com/Crypto-Legions/crypto-frontend">Frontend</a>
  - smart contract repo: <a href="https://github.com/Crypto-Legions/CGA-Games-Contracts">Smart Contract</a>
<br />
