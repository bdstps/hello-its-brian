---
layout: "../../layouts/BlogPost.astro"
title: introducing the stoopy2 token
description: i made my own cryptocurrency
pubDate: "Dec 23 2021"
---
*I promise this won’t be a cryptocurrency blog. I just wanted to share a fun Wednesday-night-before-Christmas-project I worked on.*

So as a few of you may know, earlier this year I minted my own cryptocurrency, producing 100,000,000 stoopy tokens on the Ethereum blockchain. My goal with that first experience was to produce something that other people could trade for on their own, without any interaction from me. Turns out, in order to provide the necessary liquidity to make that feasible, I would need to shovel over about $2000 in ETH. That’s not something I wanted to do.

So, as it stands, I still have 99.999 million original stoopy coins in my wallet. It’s been that way for about six months now.

But I still had that goal of one day producing liquidity, so that all three of you reading this may know the joy of owning your own stoopy coin. I knew that deploying a new contract on a different blockchain (one with much, much lower fees) was probably the way.

## creating a new token

Enter: Avalanche (AVAX). Over the course of about twenty minutes last night, I actually deployed three more contracts to mint new cryptocurrencies. Two had mistakes in them. The third one was (mostly) perfect.

This was the birth of stoopy2, or S2 for short. To be honest with you, there were still some issues with the deployment. I wanted to mint 100,000 tokens, but actually ended up minting far, far fewer. As a result of this mistake (really just a lack of understanding of how the contract reads the inputted supply metric), I minted 100 S2 tokens. [Here’s a link to the contract.](https://snowtrace.io/address/0x4a7e256ece583950816c26700d2249c175ee6f91)

To say the least about the Avalanche chain and its fees (and thus, environmental impact), it’s negligibly small. Whereas a standard contract deployment costs between $200 and $400 on the Ethereum blockchain, one on Avalanche costs mere cents.

So it’s better, at least in that regard.

## providing liquidity

The next step in my two step plan was to provide some liquidity.

I should say in advance that I did next to no research on the platform I used to create the liquidity pool, so if, for some reason, you decide you want to transact and get some of the stoopy2 token available, or even use the site to make trades for other tokens on the Avalanche chain, just know that it by no means has any endorsement from me as being “trustworthy.”

With that aside, I chose Trader Joe. It just seemed like the easiest option.

![](https://images.squarespace-cdn.com/content/v1/61c1894d76fd1365e7917b5e/27a3155e-b089-46b0-855e-77d1a3c50310/S2+on+TraderJoe?format=1000w)

For the uninitiated, when you create a liquidity pool (which is one way to enable trading on various sites), you must provide both the token you are hoping to provide liquidity for, and some other token. In my case, I chose Avalanche, which the “pairing” for all exchanges of stoopy2 will be AVAX-S2.

By doing this, you are releasing some of those tokens into the custody of the trading arbitrage, and creating a value for which it trades against. I supplied the pool with 50 S2 tokens (50%), and backed it with 0.25 Avalanche (about $30 at time of posting). This means that, if you wanted to trade for one S2 coin, you would need to supply 0.00518797 AVAX, or about 62 cents.

## how you can get some S2

If you have no desire to ever owning stoopy2 tokens, you probably don’t need to read any further. If you do want to get some tokens, I’ve got you covered.

But first, for legal reasons, it is important me to say that nothing I have said thus far, nor anything I say to follow this constitute as financial advice. The stoopy2 project was created for fun, and its purpose is never to make myself, or anyone else any financial gain. This coin has no utility and no benefits. Additionally, I do not know enough about Trader Joe to know its validity as a trading platform, and therefore would caution anyone following these steps to be aware that fraud is possible. Do your own research. Consider any investment in stoopy2 completely valueless.

- - -

Okay, with that out of the way, here’s the step by step process you’ll want to take to get some S2 in your wallet.

1. Acquire some Avalanche token — you don’t need much at all
2. Send your Avalanche token to a Web3 wallet like [Metamask](https://metamask.io)
3. Navigate to [Trader Joe](https://traderjoexyz.com#/home) and connect your Web3 wallet
4. On the trade menu, use the [stoopy2 contract address](https://snowtrace.io/address/0x4a7e256ece583950816c26700d2249c175ee6f91) to enable trading between AVAX and S2
5. Trade your available AVAX for S2

And you’re done! You might find that it doesn’t populate in your wallet of choice. To get it to show up, find the functionality in your wallet to add a custom token. It should ask you for the contract address. Everything else should auto-populate, assuming your wallet is on the Avalanche network. Accept the custom token, and it should show up in your list of assets!

If you would like a personalized guide through this process, just let me know, and I’d be happy to walk you through it.

## but why?

It’s fun. That’s it.

I’ve always been interested in crypto, in spite of its horrible effects on our environment. I don’t know what the future holds for certain commodities within this realm. But it’s fun to watch, and getting involved in this way makes me feel like I have a superpower.

I’m not a developer. I have very little knowledge when it comes to code. I simply took an open-source contract and adapted it to fit my needs, then hit a few buttons to immortalize it on the blockchain.

And for some reason, that’s just so much fun.

<!--EndFragment-->