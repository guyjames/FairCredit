# FairCredit on Holochain

## A proposal for how a mutual credit currency could work alongside FairCoin

## Developed as part of, and with the help of mentors and participants of, the Civichub course held in La Garrotxa, autumn and winter 2018.

### By Julio Monteiro and Guy James, with input by Emaline Friedman, Matthew Slater, and Chris Zumbrunn, based on the original FairCredit design by Enric Duran.

*In this document we will be referring to 'nodes' generically; a node could be a local FairCoop node, a cooperative service provider or business such as Komun or Fairkom, another sort of cooperative within the FairCoop ecosystem, or an individual FairCoop member*.

## The Issue

It has become increasingly evident that there are limitations to the current crypto-token model on which FairCoop has based its economic system. The system, as Matthew Slater notes, is that, "the crypto-token model worked well in a bull market, but otherwise doesn't seem to be helping. Maybe it's time to try something else, and here is a way that we could transition from FairCoin to FairCredit."

What seemed to be a possible minor flaw in the design of FairCoin has, thanks to the current 'crypto winter', the extent of which obviously could not have been foreseen at the outset, now become a serious problem which is causing those previously optimistic about the FairCoop project to seriously question if it has a future. This gradual leaking away of trust in the project itself and between the activists engaged in it has led to an increased level of conflict and an overall lack of harmony in the way people are working together. It appears that only a radical overhaul of the initial design can mend the rifts and bring the project back to a sustainable model.

However there is a proposal which in fact had been suggested from the very start of the FairCoop project but which has never been implemented; **this is the FairCredit proposal**, which, in a nutshell, is a mutual credit system designed to be complementary to FairCoin, the rules for issuance of which could be dependent on various ways of interacting with the existing FairCoin economy; some possible suggestions are set out below.

The FairCredit proposal could be implemented in a variety of ways, including [FairChains](http://fair-coin.org/en/fairchains), Ethereum smart contracts, or a centralised database on a server. It could even be done manually using a spreadsheet. However we feel the best way to go is to use [Holochain](https://holochain.org/) because it works very well with mutual credit currencies, it is relatively easy to develop an app using Holochain as the backend, and it complies with the FairCoop philosophy using of P2P decentralised commons-based free software technology.

The currency works like other mutual credit currencies such as those using IntegralCES, but at first, the only node which is allowed to go into a negative balance is the main FairCoop account; deciding on the credit limit on the FairCoop initial node is an important, indeed maybe *the* most important, design decision that must be made in the process of creating the structure for FairCredit. As Julio Monteiro asks, how is the credit limit for the main node determined, how is that backed? **This is the main emission rule; if this initial node has infinite credits no one will trust it.** [^EmalineComment01] [^MatthewSComment01]

The other nodes start with a zero balance and are not allowed any credit until they fulfil certain conditions, for example paying a percentage of their profits to the main FairCoop account, or buying FairCoins at the official price from [getfaircoin.net](https://getfaircoin.net). This question of how to determine credit limits for the nodes is also an important one: how do they get FairCredits, what is the limit on how negative a balance they are allowed (of course in a mutual credit system there will always be creditors and debtors), and when they are 'in negative', how can they then get back to a positive or zero balance?

Before we go to an example, a comment from Matthew Slater:
"Fair Credit should be denominated in the standard unit of account of the marketplace, which is Euros. We don't want people's credits and debts with respect to each other to change value when the faircoin price changes. That would set creditors and debtors against each other."

So for example, Alice has a cooperative web design business and decides she wants to help the FairCoop movement grow, so she decides to spend 1% of her earned profit on FairCredits - she pays FairCoop in euros, dollars, francs, or any other national or local currency, including FairCoin - to keep it simple, let's say that is €100. In return she receives an allowance of 100 FairCredits. She continues to do this each month as a way to support the commons.[^ChrisZComment01] [^JulioMComment01]

The first time she spends a percentage of her profits she will continue to have a zero credit limit, and she will actually be positive +100 FairCredits.  If she continues to spend 1% regularly (say at least three times, this is one of the parameters which would have to be determined), then she will receive a credit limit of, say, 10% of the amount she donates per month.

So if she donates 100€ per month she could earn a credit limit of 10 FairCredits, then, if after 3 months, if she doesn't spend FairCredits, she will have a balance of 300 FC, plus a -10 credit limit, so in total, she can use up to 310 FC.  The increase in credit limit could also be dependent on spending a certain amount of the FairCredits every month, in order to reward spending and earning, rather than saving.

If she continues to do that regularly, her credit limits will increase, up to a maximum percentage of her monthly payments. This is a nice way to do incentives, without creating huge inflation as with compound interests in today's deleterious capitalism. A good idea may be to have it as an average of their overall contribution (think of AirMiles and frequent flyers).

**Another example**: Bob has heard about FairCoop and wants to get involved, so he goes to getfaircoin.net and buys 100 FairCoins at the official price using bank transfer. When the transaction is completed he receives an email with a QR code which he can scan using the FairCredit app, and which increases his credit limit by 100 FairCredits. This adds significant value to buying FairCoins at the official price [^EmalineComment02]

**The above two examples show the effect of increasing the liquidity of FairCoop and of acting as a kind of reputation currency for those who have contributed to the ecosystem.** The FairCredit balances will be visible publicly by default. [^EmalineComment03]

(We should think of all the ways in which account holders could increase their credit limits and the pros and cons of each.)

Another comment from Matthew Slater: "The two examples you give of credit limits being increased are both fully automatic. There needs to be a human process, and a way of dealing with individual cases. We shouldn't try to manage trust through algorithms."

So what does FairCoop do with the fiat liquidity received, apart from keep it as a reserve used to pay merchants who want to cash out their FairCoin? It could help to set up new cooperative businesses. And what can people do with their FairCredits? They can use them to buy shares in these new coops, and be entitled to a percentage of profits generated according to how many FairCredits they have invested. In this way, the FairCredits could function as a sort of dividend.[^EmalineComment04] [^JulioMComment02]

Here's a very interesting design choice: if you invest your FairCredits on nascent coops, or existing projects needing support, besides receiving shares in that cooperative, you could also get some **EXTRA** credit limits. So when someone in the network organises a system wide **crowdfunding** event, everyone that invests FairCredits gets say, 10% of that investment back in terms of additional credit limits. Bearing in mind that one can only invest with POSITIVE credits (to avoid loopholes) [^EmalineComment05]

This is a powerful way for the network to incentivise collaboration for the commons.[^MatthewSComment02]

The FairCoop reserve accounts in the various currencies would have to be totally transparent in order that people could see where their money was going.

We could also think how the FairCoop Local Nodes could have a special role in this ecosystem - they already function as Points of Exchange (POE) in order that people can buy FairCoins with cash; possibly they could also serve as POEs to convert FairCredits into FairCoin.

This is just a draft proposal so far so any thoughts are appreciated, thanks.

------

Please see the diagram below for Julio Monteiro's initial design:

![](julio-faircredit-holochain.jpg)

-----

[^EmalineComment01]: Emaline: Thomas Greco is fairly clear that when the credit issuer has an egregious limit, things can sour quickly. holo, for example, does this because in our design there is the expectation of earning against this debt on transaction fees. is something similar planned for the main account?

[^EmalineComment02]: Emaline: Is this a hard decision NOT to honor faircoins purchased on exchanges? how will you differentiate between faircoins already owned by participating community members versus altcoin holders?

[^EmalineComment03]: Emaline: If you incentivize participation by increasing credit limits, liquidity is only in national currencies rather than actual goods and services in the ecosystem...you may actually end up encouraging a deeper connection with these currencies, rather than keeping business in the coop (also, this doesn't show the effect... the above might be the effect. Are there other effects in mind? if so, they should be here.

[^EmalineComment04]: Emaline: Isn't a cooperative business precisely one owned by workers?

[^EmalineComment05]: Emaline: Here as elsewhere i'm a little concerned about the stakes for nascent cooperatives - will they be profitable enough to participate in this structure, in terms of delivery of goods and services to the ecosystem in which credit limits are useful? Profitable enough for investors to see returns? To me, this is a high ask for non-competitive groups.

[^ChrisZComment01]: ChrisZ: If 1 FairCredit == 1 FairCoin when you have to repay a negative balance, as the FairCoin value goes up, the FairCredit will become impossible to repay. If you accumulate a negative FairCredit balance of 100 when 100 FairCoins are worth 1x, you may some years later have to pay back a value of 20x, due to the increased FairCoin value, in order to bring that FairCredit balance back to zero, which would make the concept of FairCredit negative balances unethical. If you denote the FairCredit in Fairo, you don't have that problem. This is where the concept of the Fairo comes into play... the FairCredits could be denoted in Fairo to avoid these problems. https://fairo.exchange

[^JulioMComment01]: JulioM: 1. We should decouple FairCredit value from local currencies in the reserve - if it's pegged to fiat it's bound to rise and fall with it. 2. We should have a clear way the price can shift (be it offer and demand, centralized, asset backed etc.). 3.Using Fairo could be rather risky as well, because it's a value set by a centralized "board" by "consensus" (from what I get).

[^JulioMComment02]: JulioM: Having "investors" in crowdfunding models is perhaps incompatible with coops (where the business is owned by workers no investors).

[^MatthewSComment01]: MatthewS: The difficulty of honouring all the FairCoin is that the central node would become indebted to the market cap of FairCoin. The switch-over should include only people in the system.

[^MatthewSComment02]: MatthewS: This is where it starts to get interesting, and I suspect, problematic: firstly, it's difficult to police how long a person saves a FairCoin. Secondly, you don't say whether the equivalence is bi-directional. Thirdly, by making the currencies equivalent you are effectively altering the issuance policy and the total quantity of FairCoin and saying the blockchain is only half of the FairCoin ledger. Fourthly, the document should include more detail on how the credit limit of the main node should be determined.