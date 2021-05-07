# You want a Crucible but you have no idea what you're doing

Sound familiar? Don't lie, I've seen hundreds of the same basic question in the discord now and I've only been there 24 hours.

This document aims to cover some of these questions.

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

## Should you mint a Crucible?

That is for you to decide. Ensure you understand what could gain, what you could lose, and then weigh up whether you think it's a good choice for you.

## How do you mint a Crucible?

Originally the only method was getting to grips with the official CLI tool. Fortunately, community members have since created a web-app that makes the process a lot easier. Due to the extra risk of making mistakes whilst using the CLI tool it is no longer recommended to take that approach. Please instead use [https://alchemist.farm](https://alchemist.farm)

#### Video Guides

Churchee has kindly created two videos demonstrating how things work once you've got your LP tokens. You might find these easier to follow or more informative than this text based guide:

{% hint style="info" %}
Links to Uniswap in videos may be outdated since the launch of Uniswap V3.  
Please ensure to use **Uniswap V2** or refer to our links found in this documentation.
{% endhint %}

{% embed url="https://www.youtube.com/watch?v=Ga1qcQ6x3as" %}

{% embed url="https://www.youtube.com/watch?v=i2MCYimelBM" %}

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

### 1. Getting ⚗️

Ever traded coins on Uniswap? If so you know how to do this already.

{% hint style="warning" %}
Due to low liquidity on **Uniswap V3**, extra slippage might mean you will not get the best price for your purchase. Please use our **Uniswap V2** link below to perform the token swap.
{% endhint %}

1. Head to [Swap $MIST on Uniswap V2](https://app.uniswap.org/#/swap?outputCurrency=0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab&use=V2)
2. Connect MetaMask wallet
3. You should see something like this:

    ![](https://i.imgur.com/5rzgvpf.png)

4. Enter the amount of ⚗️ you wish to purchase, ensuring you have an equivalent value of ETH remaining to use for the staking
5. Hit "Swap", make necessary approvals via MetaMask, wait for the transaction to complete
   * I found that my first two attempts failed, seemingly because they weren't being processed fast enough for the price to remain stable before they finished
   * MetaMask has the ability to let you speed up a transaction by locating it in the "Activity" tab and choosing to pay more gas for higher priority processing
6. Navigate to [https://etherscan.io/address/](https://etherscan.io/address/) to view pending transactions and all tokens associated with your account.
   * if you use MetaMask you can click the triple dots and then "View on Etherscan" to jump to it:

     ![](https://i.imgur.com/jdzodQP.png)
7. You should see your new ⚗️ displayed like the following:

    ![](https://i.imgur.com/bF9wsrg.png)

### 2. Staking ⚗️ to receive LP tokens

Ever provided liquidity on Uniswap? If so you know how to do this already.

{% hint style="danger" %}
Crucible only supports the **Uniswap V2** Liquidity Pool.   
Adding liquidity to the **Uniswap V3** pool is not compatible with the Rewards Program.
{% endhint %}

1. Head to [Add LP to $MIST on Uniswap V2](https://app.uniswap.org/#/add/v2/0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab/ETH)
   * Connect MetaMask wallet if not already done so
2. You should see something like this:

    ![](https://i.imgur.com/7paIEyF.png)

3. Enter the amounts you want to stake. Both sides need to be equal value, so changing one will change the other. You most likely just want to click the "MAX" button on the ⚗️ side
4. Hit "Stake", make necessary approvals via MetaMask, wait for the transaction to complete
5. You should see your new LP tokens \(named UNI-V2\) on Etherscan again:

    ![](https://i.imgur.com/6hAoHGw.png)

### 3. Minting the Crucible with LP tokens

{% hint style="info" %}
**Important information:** 

Do not use Brave browser as it is not compatible with the process at this time and your transaction will fail resulting in lost fees. 

We do not recommend using a hardware wallet at this time as many do not currently support EIP-712 signing. When they fix this, we can implement it.

We do not recommend you do this on a mobile
{% endhint %}

1. Firstly Head to [https://alchemist.farm/](https://alchemist.farm/)
2. Connect MetaMask wallet
3. You should see something like this:

    ![](https://i.imgur.com/eimfv0e.png)

4. Enter the amount of LP you wish you put into the Crucible. You probably wish to click "Max" to enter your full amount
5. Hit "Mint cruicible and Subscribe LP to Aludel", make necessary approvals via MetaMask, wait for the transaction to complete
6. You should see your new Crucible on Etherscan:

    ![](https://i.imgur.com/9VBX6M6.png)

## Congratulations, if you've made it this far, you're an Alchemist

Some other questions you may have:

### How do I get that fancy "Certified Alchemist" role on the Discord server?

Please follow the guide [here](how-to-become-a-certified-alchemist-on-discord.md)

### How can I check how many LP tokens is in my Crucible?

You can use [https://alchemist.farm/](https://alchemist.farm/) to view your Crucible:

![](https://i.imgur.com/WCBz8yM.png)

As you can see it also displays several other useful metrics to track the performance.

### How can I check how many LP tokens someone else's Crucible is worth?

You can take the take the Crucible's tokenId, convert it into hexadecimal if it is in decimal instead, and then search for the address on [https://etherscan.io](https://etherscan.io) to check what the contents are. If you can't see any tokens displayed for it, then it's most likely empty.

### How much LP tokens do I need to create a Crucible?

I don't know what the requirement is, but people have reported creating one with as low as 0.5 LP tokens. It would not surprise me if it was possible with 0.

Of course, a Crucible still costs gas to mint, so creating one with ~0 LP inside costs you money to create what is at present a worthless item.

Remember, you earn ⚗️ rewards proportional to your LP share of the total LP staked in the Aludel.

### Can I create multiple Crucibles?

Yes. Some people have already.

Again, every transaction is costing you in gas though, so the wisdom of creating multiple instead of just one is in question.

### How do I know if I've subscribed the LP within my Crucible?

It should be done automatically. You can also use [https://alchemist.farm/](https://alchemist.farm/) to check on your Crucible. There will be a padlock icon in the upper right corner of the Crucible display which indicates the amount of LP that has been subscribed to the Aludel reward program: ![](https://i.imgur.com/ed4d3m8.png)

### How do I check my Aludel rewards?

You can use [https://alchemist.farm/](https://alchemist.farm/) to display your Crucibles, where it will list your current ⚗️ and ETH rewards.

### If I've minted my Crucible and subscribed my LP... is that it?

Yes. Now you sit back and see what happens.

### Okay but I how do I add these tokens to MetaMask?

Fine I'll tell you, you add custom tokens with the following addresses:

⚗️ token contract address: `0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`   
⚗️/ETH UNI-V2 contract address: `0xcd6bcca48069f8588780dfa274960f15685aee0e`   
Alchemist Crucible contract address: `0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`

### I've changed my mind! How do I unstake?!

Please refer to the following guide: [How to unstake your crucible using the Taichi network](guides-alchemist.farm/how-to-claim-rewards-and-unsubscribe-your-lp-from-the-aludel-using-the-taichi-network.md)

\*\*\*\*

