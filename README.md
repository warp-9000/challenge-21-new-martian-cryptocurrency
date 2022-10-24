#  Challenge 21: New Martian Cryptocurrency

This challenge builds a fungible ERC-20 compliant token, Crowdsale, and Deployment contracts. These trio of contracts are for a fictitious Martian colony. The ERC-20 compliant token is called KaseiCoin (KAI) and will be used as the new martian currency. The Crowdsale and Deployment contracts can be deployed to simulate the minting of new KAI in a 1-1 exchange for ETH.

---

## Technologies

This smart contract is written in solidity v0.5.5 and can be compiled and run on an ethereum development network.

---

## Installation Guide

You have a few options to get this code on your computer, two popular options are:

1. Download a ZIP of this repositories files 
[here](https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/archive/refs/heads/main.zip).

2. [Fork this respository](https://docs.github.com/en/get-started/quickstart/fork-a-repo "Fork a Repo - 
GitHub Docs") to your github account.

<p align="center">
<img src="https://github.com/Warp-9000/uw-fintech-2022-module01-challenge/blob/main/instructions/github-fork-button-screenshot.png?raw=true" 
alt="Fork UI on GitHub.com"
width="55%"/>
</p>

After forking the respository you can use `git clone 
your-username@domain.com:your-git-username/challenge-21-new-martian-cryptocurrency.git` 
to download a copy of the forked respository to your computer.

Forking has the added benefit of enabling your to easily keep your copy of the 
application up-to-date should any changes or improvements be made in the future.

---

## Usage

***Please note:*** these usage instructions assume you are using an editor that can compile the solidity code and deploy the smart contract to an ethereum development network.

For example you could perform the following:

1. Load the code in `KaseiCoin.sol` and `KaseiCoinCrowdsale.sol` in <a href="https://remix.ethereum.org">remix.ethereum.org</a>.
2. Compile the code using a `0.5.x` version compiler.
3. Deploy the smart contract on `Remix VM (London)` or to local MetaMask accounts on a development blockchain in Ganache.

## Execution Results 

Below is an example of the deployment and minting of KaseiCoins

Proof the KaseiCoin contract compiled successfully:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221022-181207-KaseiCoin.sol-Compilation.png?raw=true" 
width="85%" />
</p>

Proof the KaseiCoinCrowdsale and KaseiCoinCrowdsaleDeployable contracts compiled successfully:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-203658-KaseiCoinCrowdsale.sol-Compilation.png?raw=true" 
width="85%" />
</p>

Deploying the KaseiCoinCrowdsaleDeployable contract:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-222315-DeployingContract-01.gif?raw=true" 
width="85%" />
</p>

Adding the deployed KaseiCoinCrowdsale and KaseiCoin contracts to Remix:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-222514-DeployingContract-02.gif?raw=true" 
width="85%" />
</p>

Test account ETH balances before minting KAI:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-222729-BeforePurchasingKAI.png?raw=true" 
width="85%" />
</p>

Purchasing 3 KAI:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-222907-PurchasingKAI-01.gif?raw=true" 
width="85%" />
</p>

Purchasing 5 KAI:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-223112-PurchasingKAI-02.gif?raw=true" 
width="85%" />
</p>

Purchasing 11 KAI:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-223544-PurchasingKAI-03.gif?raw=true" 
width="85%" />
</p>

Test account ETH balances after minting KAI:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-223800-AfterPurchasingKAI.png?raw=true" 
width="85%" />
</p>

The blockchain transactions from deploying the contract and minting coins:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-223943-BlockchainTransactions.png?raw=true" 
width="85%" />
</p>

The total coin supply and wei raised after minting:
<p align="center">
<img src="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/blob/main/Execution_Results/20221023-224118-TotalSupply&WeiRaised.gif?raw=true" 
width="85%" />
</p>

---

## Contributors

Thanks!

<a href="https://github.com/warp-9000/challenge-21-new-martian-cryptocurrency/graphs/contributors">
<img src="https://contrib.rocks/image?repo=warp-9000/challenge-21-new-martian-cryptocurrency" />
</a>
