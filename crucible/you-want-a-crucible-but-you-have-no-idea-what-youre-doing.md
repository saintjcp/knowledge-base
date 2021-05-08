# Teach me about Crucibles

## How do you mint a Crucible?

Originally the only method was getting to grips with the official CLI tool. Fortunately, community members have since created a web-app that makes the process a lot easier. Due to the extra risk of making mistakes whilst using the CLI tool it is no longer recommended to take that approach. 

Please use one of the guides below to mint a Crucible:

* [Minting a Crucible on crucible.alchemist.wtf](guides-crucible.alchemist.wtf/)
* [Minting a Crucible on alchemist.farm](guides-alchemist.farm/how-to-get-your-crucible.md)

## What is a Crucible worth?

The value of a Crucible is difficult to determine because the project is young. The NFT nature of the Crucible could potentially make it have speculative value beyond the its immediate worth.

Speculation aside, however, what we do know is that a Crucible is created with some variable amount of LP tokens inside which have an immediately measurable value - how much could you get if you used those LP tokens to unstake the ⚗️ and ETH from a pool and then traded those back to whatever your favourite base currency is.

Refer to the FAQ section below for methods to check the contents of a Crucible.

If you do not know of a way to determine a Crucible's contents accurately, I strongly advise not buying Crucibles - they remain non-scarce right now, and you can mint your own for a cost you know is fair for what you get.

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

## What wallets can I use to store my Crucible?

Crucibles are ERC-721 tokens and signing these transactions are not supported by all Wallet Applications. 

Please refer to our [wallet compatibility guide.](wallet-compatibility.md)

## How much LP tokens do I need to create a Crucible?

I don't know what the requirement is, but people have reported creating one with as low as 0.1 LP tokens.

Of course, a Crucible still costs gas to mint, so creating one with minimal LP inside costs you money to create what is at present a worthless item.

Remember, you earn ⚗️ rewards proportional to your LP share of the total LP staked in the Aludel.

## Can I create multiple Crucibles?

Yes. Some people have already.

Again, every transaction will cost you gas, so the wisdom of creating multiple instead of just one is in question.

## How can I check how many LP tokens someone else's Crucible is worth?

You can take the take the Crucible's token ID, convert it into hexadecimal if it is in decimal instead, and then search for the address on [https://etherscan.io](https://etherscan.io) to check what the contents are. If you can't see any tokens displayed for it, then it's most likely empty.

## Okay but I how do I add these tokens to MetaMask?

Fine I'll tell you, you add custom tokens with the following addresses:

⚗️ token contract address: `0x88acdd2a6425c3faae4bc9650fd7e27e0bebb7ab`   
⚗️/ETH UNI-V2 contract address: `0xcd6bcca48069f8588780dfa274960f15685aee0e`   
Alchemist Crucible contract address: `0x54e0395CFB4f39beF66DBCd5bD93Cca4E9273D56`

## I've changed my mind! How do I unstake?!

Please refer to the following guide: [How to unstake your crucible using the Taichi network](guides-alchemist.farm/how-to-claim-rewards-and-unsubscribe-your-lp-from-the-aludel-using-the-taichi-network.md)

\*\*\*\*

