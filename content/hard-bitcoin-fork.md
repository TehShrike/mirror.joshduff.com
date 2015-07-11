# It's Time For a Hard Bitcoin Fork

[Source](http://hackingdistributed.com/2014/06/13/time-for-a-hard-bitcoin-fork/)

*Friday June 13, 2014 at 02:05 PM Ittay Eyal, and Emin Gün Sirer*

A Bitcoin mining pool, called GHash and operated by an anonymous entity called CEX.io, just reached 51% of total network mining power today. Bitcoin is no longer decentralized. GHash can control Bitcoin transactions.

## Is This Really Armageddon?

Yes, it is. GHash is in a position to exercise complete control over which transactions appear on the blockchain and which miners reap mining rewards. They could keep 100% of the mining profits to themselves if they so chose. Bitcoin is currently an expensive distributed database under the control of a single entity, albeit one whose maintenance requires constantly burning energy -- worst of all worlds.

Some people might say that this is a sensational claim. It's not. The main pillar of the Bitcoin narrative was decentralized trust. That narrative has now collapsed. If you're going to trust GHash, you might as well store an account balance on a GHash server and do away with the rest of Bitcoin -- we'd all save a lot of energy. This is a big deal, and it would be a mistake to downplay it in the hope to buoy Bitcoin prices. It will be difficult to attract new people to Bitcoin when it's controlled or controlable by a single entity. If those people were willing to trust a single entity, they could have dodged inflation by putting their fiat into World of Warcraft or subway tokens. They came to Bitcoin because it was decentralized, and now it isn't. The first step is to admit that we have a problem. Luckily, there is life after Armageddon, and there are possible fixes to get back to normal from here.

Some pedants might point out that GHash reaching 51% over a 12-hour period doesn't mean they actually have 51% of the hashing power. GHash might just have gotten lucky. That's true, but they got lucky not just once, or twice, but over the span of 72 blocks. Laws of large numbers do apply. And even if they are really at 49.9% and "only" had a lucky long streak, their steady growth over the last year shows that they will soon have 51% if they don't already.

In a possibly unrelated, or possibly very related development, someone has been using spare mining capacity to attack Eligius. Essentially, someone has been pretending to be part of the Eligius mining pool and submitting near-solutions to cryptopuzzles in order to collect a share of any blocks discovered by Eligius. But these same people have simply been discarding any blocks they discover, so Eligius pays them for their effort, but they don't contribute anything to the pool. Note that the attacker doesn't gain anything from this behavior, either; it's purely destructive. This is not rational behavior in a simple game theoretic sense -- the only sensible explanation is that it is a competing miner that is using its spare capacity to dilute Eligius' profits to drive customers away from Eligius. It's a dog eat dog world among miners with very complex incentives.

## What Happens At Armageddon?

It's critical to note that there is a difference between having 51% of the mining power, and launching a 51% attack. An honest, benign 51%er (and we'd expect GHash to be on their best behavior in the next few weeks to not spook everyone) will continue to operate normally. But 51%er can turn dishonest at any moment, for there is a huge difference between someone who only holds 49% of the revenue, and someone who holds 51%. A 49%er can collect only 49% of the rewards if they are honest; if they engage in selfish mining, they can collect almost 100% of the rewards, but they cannot launch a full 51% attack. A 51%er can collect 100% of the mining rewards. In addition, they can reject every block found by competing miners and selectively drive them bankrupt. They can reject selected transactions. They cannot take away your Bitcoins but they can make certain addresses unspendable. And that allows them to extort any mining fee they like. They are a de facto monopoly.

Most religious texts claim that the devout and the righteous will disappear suddenly when the day of reckoning comes, while the remaining people are left to roam the earth. So there is life after armageddon, where the left-behinds can still inhabit Bitcoin talk forums and push their favorite cryptocurrency while badmouthing competing alt-coins. Religious texts tell us that sinners will continue to lie and cheat and steal, collect donations to improve the talk forums but spend them on extracurricular activities, or do Bitcoin IPOs and abscond with the cash or just gamble the cash away. Andreas, the confident messiah of the Bitcoin crowd who, as far as I can tell, has no technical qualifications and an abysmal track record where he did not see the impending Mt. Gox collapse and shilled for Neo & Bee, will probably make another appearance, trying to dispense holy KoolAid to the folks who bought at $1200.

But the fact is, this is a monumental event. The Bitcoin narrative, based on decentralization and distributed trust, is no more. True, the Bitcoin economy is about as healthy as it was yesterday, and the Bitcoin price will likely remain afloat for quite a while. But the Bitcoin economy and price are trailing indicators. The core pillar of the Bitcoin value equation has collapsed.

## Implications

Interestingly, when we first discovered selfish mining and cautioned Bitcoiners about a resulting 51% attack, our blog got brigaded by the Bitcoin lunatic fringe. Their main argument was "No miner would do that, it'd be against their self-interests. Why, they would destroy their own investment!" We have preserved almost all of those comments intact (we did delete a few that had profanities). It's interesting to see how obnoxiously the lunatic fringe was pushing on this point, how strongly they claimed that every single miner would be devoted to the long-term well-being of the currency, how utterly convinced they were that no one would engage in any behavior that might take a pool past the 51% point.

The main ringleader of this brigade was a failed academic from Singapore, someone who had a superficial knowledge of game theory and sufficient familiarity with Latex to create the look & feel of research papers, but someone whose own academic work never went beyond repackaging well-known results in game theory. He kept claiming that a miner reaching 51% was equivalent to "mutual assured destruction." This was, of course, all just noise. We tried to point out that there are lots of different players in the Bitcoin universe, that not everyone will have the long-term best interests of the currency in mind, that someone could enroll the help of partially rational or short-term rational miners to their cause. But it's hard to argue rationally with people who have money at stake. Bitcoin was going to go to the moon, and we were bad people (the actual words used were far worse) for pointing out a part of objective, inescapable reality that interfered with their plans to get rich. By God, they were entitled to retire based on the fruits of their graphics cards, everyone was an early adopter no matter how late, and, they were heavily vested in Bitcoin, convinced of a hyperinflationary future to come. "Trust math" they said, but only when it served to advance their market position. Even though we provided a fix for the problem we identified, they tried to drown out our message, math be damned.

A secondary argument these people latched onto was that "the developers would never allow that to happen." I never understood how anyone could simultaneously claim that Bitcoin was the future of currencies, and yet could entrust that future to the diligence of a handful of developers. It's great to see that people believe that a dozen developers can actively respond to all events that threaten a $10B currency system, but what if Armageddon happened while they were at a conference in Barbados with us? In any case, the core developers seem to be nowhere to be found at this monumentous occasion, except Peter Todd wrote that he is liquidating half his Bitcoins and Luke-Jr posted earlier today that Bitcoin was just an experiment.

No one knows the ultimate aims of GHash. The people who join the GHash pool do so because GHash has zero fees -- these people are essentially optimizing for short term profits over the long term well-being of the currency. All of these are precisely the points we cautioned about.

So this is when we get to say "We told you so."

## What Not To Do

The knee-jerk reaction from the Bitcoin lunatic fringe will be to try to minimize the issue. The folks who are vested upto their eyeballs in Bitcoin will now claim that, surely, GHash would be crazy to launch a 51% attack, even though they control 51%.

But that's exactly the same reasoning they used before GHash reached 51%. People were claiming that GHash or any other miner would be crazy to even reach 51%, and look where we are now.

Worse, GHash has a well-known track record of actually engaging in double-spend attacks even when they did not command a majority of the hashing power. GHash used its hashing power to attack a gambling site that accepted 0-confirmation transactions. In essence, they would make a bet, as in red-or-black in roulette, and if the virtual roulette wheel spin came out the wrong way, they would cancel their losing bet and place a new one. This is outright theft: GHash stole from a gambling operator.

Besides GHash, other miners have used 51% attacks to destroy alternative cryptocurrencies. In particular, Luke Jr apparently used the Eligius pool to attack CoiledCoin. 51%ers are dangerous under the best of circumstances, and even if one could trust a particular entity, their centralization makes them vulnerable to takeover by parties with different intentions.

Overall, there is absolutely no reason to trust GHash or any other miner. People in positions of power are known to abuse it. A group with a history of double-expenditures just blithely went past the 51% psychological barrier: this is not good for Bitcoin.

And why should any miner have Bitcoin's long-term future in mind? A common response to this question is "because of their investment in their mining equipment." This response is broken because it assumes a static world. Instead, the mining rigs have a fairly short useful lifetime. If a miner knows that they will be overtaken by the next generation of hardware about to be unleashed by a competing mining pool, it will have a definite time horizon for extracting every last bit of value, and that plan may not have room in it for a voyage to the moon.

## What To Do Now?

It's time for a hard fork. Such a hard fork needs to fix three outstanding, fundamental problems related to the broken incentives of the mining protocol:

It should disincentivize mining pools. Techniques for doing so are well-known. They rely on structuring the blocks in such a way that a pool member can steal the rewards for a block she finds.

It should fix selfish mining. It's only a matter of time before a selfish miner emerges in the Bitcoin scene; in fact, we suspect it was solely the presence of big mining pools, and their peering arrangements, that thankfully kept selfish mining at bay since we disclosed the idea last November.

It should incorporate changes to make what's happening among the miners easier to detect. At a minimum, the network should publish all blocks with difficulty close to the current difficulty. The default network behavior obliterates all traces of competing blocks inside the network, which enables selfish mining to take place undetected.

The hard fork need not respect the existing blockchain (in which case, it would be a new currency with new rules and a fresh blockchain) but it should. That would enable the system to retain the Bitcoin name, and keep everyone's existing investment in Bitcoin intact. The Bitcoin system weathered a hard fork just slightly over a year ago, and can pull off another one again.

Or we can carry on as if nothing of importance happened. GHash will be on their best behavior for the next few weeks, and Bitcoin will limp along. What will bring the actual demise of Bitcoin is the subject of a future blog post, but this is by no means the end. People can still use Bitcoin to buy drugs, trinkets from Overstock.com, and maybe even grilled cheese from a food truck. There is an afterworld. And for everything else, there is dirty fiat and Mastercard.

But the sensible thing to do is to implement the few simple fixes to align miners' incentives with those of the greater Bitcoin community. Once pools are eliminated, the constant pleas on Bitcoin forums to avoid the biggest mining pool will cease. Once selfish mining is fixed, there will be no fear that large (>33%) miners will unilaterally deviate from the honest protocol prescribed by Satoshi to mine selfishly and obtain rewards out of proportion with their mining power. And once the network propagates all orphans, it'll be easy to detect the small (<33%) selfish miners. These fixes do not make Bitcoin perfect, and there may still be other issues to fix, but they fix the most important issues in a way that respects the existing investment in Bitcoin infrastructure.
