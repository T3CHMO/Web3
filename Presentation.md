# Web3
Presentation about Web 3.0

Agenda
1. WEB 1.0, 2.0 and 3.0
2. Decentralization
3. World computer
5. Wallets
6. Transactions
7. PoW vs PoS
8. Nodes
9. Smart contracts
10. Architecture
11. Storage
12. DEFI
13. Tokens
14. NFTs
15. Demo
16. Problems

# Different WEB's #
* Web 1.0 readonly, static, few users, only some companies
* Web 2.0 social media, online shopping, web as we know it today in mainstream, controled by corporations
* Web 3.0 owned by users, decentralized with no intermediaries, new business models 

![image](https://images.ctfassets.net/6g4gfm8wk7b6/7c535zBiycZLdLW1e8TTcv/2996e54c9eb3c812e272e431edf146ad/21.12.02_Web3.png?w=1860&fm=jpg&fl=progressive)
![image](https://user-images.githubusercontent.com/38141864/151798478-2bbeb9ed-b7a6-4ab9-b43e-f8f317209626.png)


# Decentralization #
* Think about your accounts, are you really own them?
* No single point of failure
* Cloud is only someone else computer, and it could be shutdown
* True ownership = not your key's not your crypto
* Asset could be taken anyware, this is true Metaverse

![image](https://user-images.githubusercontent.com/38141864/151431595-00e8265e-aff9-43d4-a85f-b8a427c78d7c.png)

# World computer #
![image](https://user-images.githubusercontent.com/38141864/151432185-828055ff-f933-461e-b210-7e3f68c27c55.png)

* Ethereum founded in 2016 
* Blockchain with not only payments, but with ability to execute code in decentralized way = Smart contract
* Enables to create dApps, Tokens, NFTs.
* After deployment code can't be changed

![image](https://user-images.githubusercontent.com/38141864/151434669-af99308e-bea7-475c-924c-3b4ee4b5419e.png)

# Decentralization trilemma #
* New EVM forks are compromising on DECENTRALIZATION or SECURITY to gain speed.
* Ethereum is slow, and demant is huge -> High transaction fees
* Scailing blockchains using Layer 2 
* Ethereum currenty 4 TPS, using L2 we can scale to 10 000 TPS not compromising DECENTRALIZATION or SECURITY.
* L2 are posting cryptographic proofs to L1 

https://ethtps.info/

![image](https://user-images.githubusercontent.com/38141864/151760555-a63a5347-a067-41ec-aeeb-75f658c79c4b.png)

# Proof of work vs proof of stake #
* Transaction needs to be mined or validated to be added to blockchain
* Difference between PoW and PoS
*  PoS will be shipped in 2022

![image](https://user-images.githubusercontent.com/38141864/151436862-d5cbea24-6fab-4391-9117-f854e9029891.png)

# Wallets #

* Two types of accounts
  * Externaly owned account
  * Smart contract  
* Public key 0x8c70d45566F6786CEFCb15C9c9570407f826f5c9
* A private key is nothing else than 64 random hex characters, never share it! :)
* Not your key's not your crypto

![image](https://user-images.githubusercontent.com/38141864/151434979-40330c4e-1667-492d-bc9d-a8d88b0691e1.png)

# Transactions #
* Reading blockchains is free
* Writing to it requires fee = GAS
* Examine transactions on Etherscan https://etherscan.io/

# Node #
* Key element of infrastructure, maybe most important
* Node != Miner/Validator
* Everyone should be able to run a node
* Node services

# Smart contracts #

![image](https://user-images.githubusercontent.com/38141864/151758893-c377e21f-9447-446e-beb8-10ddc303b3b0.png)

* Solidity is programming language for Ethereum Virtual Machine (EVM)
* Solidity code is compiled to bytecode which is deployed to network by transaction 
* Bytecode is running in EVM when transaction is mined/validated - only when changing state of blockchain
* ABI - application binary interface is used to inrteract with backend
* OpenZeppelin - standart implementation of interfaces https://openzeppelin.com/contracts/
* Full deterministic, random number can't be generated
* Oracles - protocols that use smart contracts to provide off-chain data, random numbers 
* Remix IDE https://remix-project.org/

![image](https://user-images.githubusercontent.com/38141864/151759959-d3ec23c9-5a6c-443a-a101-08cc616a710c.png)


# Architecture #

* Blockchain is a backend
* Frontent is using web3.js or ethers.js libraty to interact with backend

![image](https://user-images.githubusercontent.com/38141864/151440624-f7630b40-a3b3-4612-b9e8-f92329f24685.png)

# Storege #

![image](https://user-images.githubusercontent.com/38141864/151760112-27f3fedc-0ee9-4ec9-a080-465dcaaea39b.png)

* IPFS - interplanetary file system
* Content-based storage instead of location-based
* File must be pinned
* Hash is generated during upload, file cant be changed
* Website can be hosted on IPFS

![image](https://miro.medium.com/max/1310/0*1rGbLPMxd_6CwFCJ)

# TOKENS #

* Fungible tokens - ERC-20
 * Stablecoins
 * Governance tokens
 * Any other tokens 
* Non-fungible tikens - ERC-721
 * Art
 * Game items 

# NFT's # 

* Overpriced jpegs
* True ownership of unique digital item
* Game items can be used in different games
* True metaverse
* Liquidity provides

![image](https://user-images.githubusercontent.com/38141864/151798651-cbe46441-10b8-4fff-b69f-b6020d70ad64.png)
![image](https://cdn.wallpapersafari.com/6/83/w845fo.png)
![image](https://user-images.githubusercontent.com/38141864/151765226-df06f260-a684-4f39-b5f2-ade10f6faf27.png)

# DEFI #

![image](https://user-images.githubusercontent.com/38141864/151808169-e617d0a8-1c14-4e9f-a105-838e84bd0034.png)

* Decentralized finance - finantial products that anyone can used and benefit from
* DEFI is offering 11% on stablecoins, new strategies are being explored
* Users can borrow your assests and pay interest to you. Without intermediaries.
* https://compound.finance/markets
* https://aave.com/

![image](https://user-images.githubusercontent.com/38141864/151437688-d006eb02-efba-4057-8134-4288142ff452.png)

* This is already happening, fintech are in the first line, but banks are following.
* Not all users want to menage their private keys in proper way. Banks or fintechs will do that for them. 

# DEMO # 

Demo dApp repository
https://github.com/dappuniversity/dbank

![image](https://user-images.githubusercontent.com/38141864/151765682-da002f15-0505-43c7-a330-8ee2b08ac5e6.png)

# OVERVIEW #

![image](https://user-images.githubusercontent.com/38141864/151795611-8ae73667-9fdb-4e16-bf4f-13ade20c66ef.png)


# Problems #
* High gas fees - L2
* Decentralized storage options - IPFS, more options needs to be explored
* Wallets - Social wallets and recovery
* Scams
* PoW - energy consumption -> PoS reduce consumption by 99%

# Questions #
* Do you have any questions?










