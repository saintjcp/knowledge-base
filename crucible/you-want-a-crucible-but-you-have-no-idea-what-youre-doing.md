# Tell me more about Crucibles

## The basic outline

There is a token called Alchemist. It has the ticker symbol "⚗️". It is also referred to as "mist" and "$MIST". Do not confuse it with [MUST](https://www.coingecko.com/en/coins/must) - despite the alembic it now displays it has no relation to Alchemist.

What is ⚗️ good for? I am not here to answer that. Please refer to the [official FAQ](../alchemist-faq-usdmist.md)

You can stake ⚗️ as with other coins, and you can ultimately use it to mint Crucible NFTs.

## How could I increase my wealth using ⚗️?

### 1. Speculation

The first way is to speculate on its value. In other words: you buy some and hope the price goes up and then sell it. Disclaimer: there is no guarantee the price goes up.

### 2. Staking

{% hint style="danger" %}
Crucible only supports the **Uniswap V2** Liquidity Pool. Adding liquidity to the **Uniswap V3** pool is not compatible with the Rewards Program.
{% endhint %}

The second way is to stake it in a liquidity pool alongside an equal value portion of Ether \(ETH\). When you do so you receive Liquidity Pool tokens \(LP\) that represent your stake in that pool. Ultimately these LP tokens are used to withdraw your original ⚗️ and ETH from the pool when you decide you are finished with it.

The liquidity pool is used to facilitate trades between ⚗️ and ETH that other people wish to make. Every trade made incurs a small fee for the person making the trade. Whilst you hold LP tokens, you receive a portion of those fees, proportional to the LP you hold relative to the total LP. \(For example, if your LP makes up 1% of the total LP then you receive 1% of the pool fees\)

This profiting from liquidity pool fees mechanism is no different to staking any other coin in any other liquidity pool. As such, it is susceptible to "impermanent loss" whereby as a staker you lose money by withdrawing your staked coins after their relative value has shifted since you staked them. If you are unfamiliar with this concept I recommend doing further research until you understand it - there are plenty of resources explaining it better than I could.

{% embed url="https://youtu.be/8XJ1MSTEuU0" caption="Please watch this video on \"Impermanent Loss\" before proceeding." %}

### 3. Aludel

This is where the alchemy happens. "Aludel" is the name of the reward program where you can gain ⚗️ and ETH for subscribing to it with the LP tokens in your Crucible.

What is a Crucible? It's an NFT representing the LP you have staked. The act of creating one is referred to as "minting".

When a Crucible has LP subscribed to the Aludel the holder gains ⚗️ and ETH. The total rewards available is 50% of the ⚗️ created by the 1% inflation that occurs every 14 days, and the ETH raised during the initial Balancer pool. Crucibles with subscribed LP receive a fraction of the total rewards based on the fraction that their subscribed LP is of the total LP that has been subscribed and the length of time their LP has been subscribed versus the other LP.

What is an NFT? It stands for Non-Fungible Token. If that word is too big for you, you can think of "non-fungible" as meaning "unique".

NFTs are a direct contrast to coins:

* Coins: 1⚗️ is 1⚗️, they have equivalent value and use
* NFTs: 1 Crucible NFT is not another 1 Crucible NFT and it is very unlikely that any two Crucibles have equivalent value

This is an important point to understand, because people have [already listed](https://opensea.io/assets/0x54e0395cfb4f39bef66dbcd5bd93cca4e9273d56/620479970925497750675476517677400441094103376596) their Crucibles for sale on platforms such as OpenSea. At the time I write this that Crucible is being listed for 0.77 ETH. Is it worth that?

It's worth mentioning for the sake of clarity: if you mint a Crucible, you are still also staking ⚗️ in the Uniswap liquidity pool as well. You are effectively engaging in all 3 ways of potentially earning.

## What is a Crucible worth?

The value of a Crucible is difficult to determine because the project is young. The NFT nature of the Crucible could potentially make it have speculative value beyond the its immediate worth.

Speculation aside, however, what we do know is that a Crucible is created with some variable amount of LP tokens inside which have an immediately measurable value - how much could you get if you used those LP tokens to unstake the ⚗️ and ETH from a pool and then traded those back to whatever your favourite base currency is.

Refer to the FAQ section below for methods to check the contents of a Crucible.

If you do not know of a way to determine a Crucible's contents accurately, I strongly advise not buying Crucibles - they remain non-scarce right now, and you can mint your own for a cost you know is fair for what you get.

## How do you mint a Crucible?

Originally the only method was getting to grips with the official CLI tool. Fortunately, community members have since created a web-app that makes the process a lot easier. Due to the extra risk of making mistakes whilst using the CLI tool it is no longer recommended to take that approach. 

Please use one of the guides below to mint a crucible

* [Minting a Crucible on crucible.alchemist.wtf](guides-crucible.alchemist.wtf.md)
* [Minting a Crucible on alchemist.farm](guides-alchemist.farm/how-to-get-your-crucible.md)

## Should you mint a Crucible?

That is for you to decide. Ensure you understand what could gain, what you could lose, and then weigh up whether you think it's a good choice for you.

#### The cost of minting

When you're dealing with Ethereum based tokens and contracts you're facing gas fees at every stage. In my case I created a Crucible containing LP worth 0.8 ETH. The process cost me ~0.1 ETH. Gas prices fluctuate, so you might find your costs are different to mine. The minting guide indicates that 0.5 ETH is "more than enough" for the minting step specifically. The other steps will cost gas too. I cannot give an estimated safe amount to guarantee you have enough gas for the entire process but you can use the figures here as a reference point and make your own call.

Obviously, depending on how much gas it costs you, there is questionable purpose in minting a Crucible with a low LP value. If I made a Crucible with 0.1 ETH's worth of LP inside it and it cost me an additional 0.1 ETH in gas fees then I would need ⚗️ to double in value to break even on my investment before even considering the gas cost of withdrawing, unstaking and selling.

#### The math

I'll work through an example to give an idea of how you split your overall investment up throughout this process. This is for demonstrative purposes, detailed instructions on how to complete each step can be found further down.

* started with 1 ETH
* set aside 0.2 ETH to cover what I anticipated the gas fees to cost
* left with 0.8 ETH to turn into LP tokens
* to stake in the liquidity pool you need equal value ⚗️ and ETH
* in this case that means 0.8 / 2 = 0.4 ETH and 0.4 ETH's worth of ⚗️
* trade 0.4 ETH for ⚗️
* now have ~14 ⚗️ , 0.4 ETH, and some spare ETH set aside for gas
* stake the ⚗️ and equivalent value ETH. Might have some of one side left over because their price has changed by the time you come to stake
* now have ~2 LP tokens, ~0 ⚗️, ~0 ETH and some ETH set aside for gas fees
* mint a Crucible with ~2 LP tokens

#### The tools

I wrote a guide but I'm no master of the craft. I haven't touched a wallet that isn't MetaMask so I cannot give advice on how to accomplish this with other software. For advice on that I recommend asking around in the [discord](http://discord.alchemist.wtf).

MetaMask does not recognise the tokens we will encounter, but they can be added as custom tokens. You can refer to the FAQ section below for instructions on that process but the guide will instead demonstrate how Etherscan can be used to confirm you have your tokens.

**Reminder**

I will include the direct links required through the next steps but you should be paranoid and verify them against the addresses listed at [https://github.com/alchemistcoin/alchemist](https://github.com/alchemistcoin/alchemist)

As an aside, I am not eager in connecting this guide with my public identity, and I don't have the spare funds to replicate this process either and didn't take screenshots when I first minted my Crucible. As such the images below are created with me editing the web pages to provide clean examples without identifying hashes. If you spot any oddities in the numbers or formatting, this is why.

## How much LP tokens do I need to create a Crucible?

I don't know what the requirement is, but people have reported creating one with as low as 0.5 LP tokens. It would not surprise me if it was possible with 0.

Of course, a Crucible still costs gas to mint, so creating one with ~0 LP inside costs you money to create what is at present a worthless item.

Remember, you earn ⚗️ rewards proportional to your LP share of the total LP staked in the Aludel.

## Can I create multiple Crucibles?

Yes. Some people have already.

Again, every transaction is costing you in gas though, so the wisdom of creating multiple instead of just one is in question.

## How can I check how many LP tokens someone else's Crucible is worth?

You can take the take the Crucible's tokenId, convert it into hexadecimal if it is in decimal instead, and then search for the address on [https://etherscan.io](https://etherscan.io) to check what the contents are. If you can't see any tokens displayed for it, then it's most likely empty.

## Okay but I how do I add these tokens to MetaMask?

Fine I'll tell you, you add custom tokens with the following addresses:

⚗️ token contract address: `0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`   
⚗️/ETH UNI-V2 contract address: `0xcd6bcca48069f8588780dfa274960f15685aee0e`   
Alchemist Crucible contract address: `0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`

## I've changed my mind! How do I unstake?!

Please refer to the following guide: [How to unstake your crucible using the Taichi network](guides-alchemist.farm/how-to-claim-rewards-and-unsubscribe-your-lp-from-the-aludel-using-the-taichi-network.md)

\*\*\*\*

