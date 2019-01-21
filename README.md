# FairCredit on Holochain

## A proposal for how a mutual credit currency could work alongside FairCoin

### By Julio Monteiro and Guy James, with input by Emaline Friedman, based on the original FairCredit design by Enric Duran.

*In this document we will be referring to 'nodes' generically; a node could be a local FairCoop node, a cooperative service provider or business such as Komun or Fairkom, another sort of cooperative within the FairCoop ecosystem, or even an individual FairCoop member*.

This proposal could be implemented in a variety of ways, including FairChains, Ethereum smart contracts, or a centralised database on a server. It could even be done manually using a spreadsheet. However we feel the best way to go is to use Holochain because it works very well with mutual credit currencies, it is relatively easy to develop an app using Holochain as the backend, and it complies with the FairCoop philosophy using of P2P decentralised commons-based technology.

The currency works like other mutual credit currencies such as IntegralCES, but at first, the only node which is allowed to go into a negative balance is the main FairCoop account; the actual limit on the FairCoop initial node should be the same as the total amount of FairCoin minted so far, and should not increase without any explicit rule (like doing a crowdfunding, getting new investors, 
and so on). [^EmalineComment01]

The other nodes start with a zero balance and are not allowed any credit until they pay a percentage of their profits to the main FairCoop account, or buy FairCoins at the official price from getfaircoin.net.

So for example, Alice has a cooperative web design business and decides she wants to help the FairCoop movement grow, so she pays 1% of her earned profit to FairCoop in euros, dollars, francs, or any other national or local currency, including FairCoin - to keep it simple, let's say that is €120. In return she receives an allowance of 100 FairCredits (the FairCredit value is always pegged to the official FairCoin price, currently €1.20). She continues to do this each month as a way to support the commons.

The first time she donates a percent of her profits she will continue to have a zero credit limit, and she will actually be positive +100 FairCredits.  If she continues to donate 1% fees regularly (say at least three times), then she will receive a credit limit of, say 10% of the amount she donates per month. 

So if she donates 100€ per month, she could earn a credit limit of 10 FairCredits, then, if after 3 months, if she doesn't spend FairCredits, she will have a balance of 300 FC, plus a -10 credit limit, so in total, she can use up to 310 FC. This of this 10 credit limit as a **"kind-of-interest"** on her investments. So if she continues to do that regularly, her credit limits will increase, up to a maximum percentage of her monthly donations. This is a nice way to do incentives, without creating huge inflation like with actual compound interests in today's deleterious capitalism.

Another example: Bob has heard about FairCoop and wants to get involved, so he goes to getfaircoin.net and buys 100 FairCoins at the official price using bank transfer. When the transaction is completed he receives an email with a QR code which he can scan using the FairCredit app, and which increases his credit limit by 100 FairCredits. This adds significant value to buying FairCoins at the official price [^EmalineComment02]

**The above two examples show the effect of increasing the liquidity of FairCoop and of acting as a kind of reputation currency for those who have contributed to the ecosystem.** The FairCredit balances will be visible publicly by default. [^EmalineComment03]

So what does FairCoop do with the liquidity received, apart from keep it as a reserve used to pay merchants who want to cash out their FairCoin? It could help to set up new cooperative businesses. And what can people do with their FairCredits? They can use them to buy shares in these new coops, and be entitled to a percentage of profits generated according to how many FairCredits they have invested. In this way, the FairCredits could function as a sort of Universal Basic Income.[^EmalineComment04]

Here's a very interesting design choice: if you invest your FairCredits on nascent coops, or existing projects needing support, besides receiving shares in that cooperative, you could also get some **EXTRA** credit limits. So when someone on the network organises a system wide **Crowdfunding**
event, everyone that invests FairCredits gets say 10% of that investment back in terms of additional credit limits. Bearing in mind that one can only invest with POSITIVE credits (to avoid loopholes) [^EmalineComment05]

This is a powerful way for the network to incentivise collaboration for the commons.

FairCredits can also be converted to FairCoin at any time, on the condition of saving them for a period of time. These FairCoins would come from a FairCoin cash fund especially created for FairCredit, which in turn could come from the Pooled Fund.[^EmalineComment06]

The FairCoop reserve accounts in the various currencies would have to be totally transparent in order that people could see where their money was going.

We could also think how the FairCoop Local Nodes could have a special role in this ecosystem - they already function as Points of Exchange (POE) in order that people can buy FairCoins with cash; possibly they could also serve as POEs to convert FairCredits into FairCoin.

This is just a draft proposal so far so any thoughts are appreciated, thanks.

------

Please see the diagram below for Julio's initial design:

![](https://i.imgur.com/M0ZDqz3.jpg)

-----

[^EmalineComment01]: Thomas Greco is fairly clear that when the credit issuer has an egregious limit, things can sour quickly. holo, for example, does this because in our design there is the expectation of earning against this debt on transaction fees. is something similar planned for the main account?

[^EmalineComment02]: Is this a hard decision NOT to honor faircoins purchased on exchanges? how will you differentiate between faircoins already owned by participating community members versus altcoin holders?

[^EmalineComment03]: If you incentivize participation by increasing credit limits, liquidity is only in national currencies rather than actual goods and services in the ecosystem...you may actually end up encouraging a deeper connection with these currencies, rather than keeping business in the coop (also, this doesn't show the effect..the above might be the effect. are there other effects in mind? if so, they should be here.

[^EmalineComment04]: Isn't a cooperative business precisely one owned by workers?

[^EmalineComment05]: Here as elsewhere i'm a little concerned about the stakes for nascent cooperatives - will they be profitable enough to participate in this structure, in terms of delivery of goods and services to the ecosystem in which credit limits are useful? Profitable enough for investors to see returns? To me, this is a high ask for non-competitve groups.

[^EmalineComment06]: Pooled fund? is this the initial node that also holds the reserves? also, does this mean Fair Coop is trying to buy up all available faircoin from exchanges and non-active holders?
