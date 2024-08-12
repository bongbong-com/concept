Abstract
-
A Factions project that works in the interest of the player, not profits.
Factions in 2016 **was** better; nostalgia aside, the game was objectively
more organic and intuitive. These are attributes necessary for a sustainable
game. Incentive systems can be re-aligned to ensure player's interest are 
held above profits. Leveraging new technology, the decade old game can
be restored to glory.

Introduction
-
As of August 11th, 2024, nearly two thousand people have joined Mineage's
mission to recreate OG Factions. However, just two weeks after SOTW, 
peak player counts have dropped from nearly 100 to barely over 10. This is to no fault
of the
server's admin. It is due to a fundamental flaw in the project's vision:
simply running 2016 plugins won't recreate the 2016 experience. The game 
of Factions, for better or worse, has evolved.
Past the "Golden Age" of Factions, circa 2016., servers have naturally acted
in their own self-interest to maximize profits. Pandering to competitive
players who spend big has come at the expense of casual players. 
All **new** players play casual Factions before entering the competitive scene; 
prioritizing competitive play at the expense of casual play is profitable in
the short-term, but kills the game in the long-run. 

It is impossible to reverse evolution. This is where Mineage gets confused. 
Rather than recreating OG Factions itself, we must recreate the OG Factions
**experience**. Stemming from the "Golden Age" of Factions, a new, unique path
can be forged. Our mission must be to bring the game we so love to the next
generation of players; pandering to the ever-shrinking current Factions 
community is not sustainable. Ten years after it's popularization by
TheCampingRusher, it's time for Factions to be reborn: with assurances.


Authority and Sustainability
-
Foremost, the root issue of profit-seeking servers must be addressed; without
addressing this issue, everything will remain the same and the game will die.
Server admins must be held accountable to act in the player's best interest.
There is only one way to do this: make all server software free and 
open-source (FOSS). The positive effects of this will be far-reaching, including:

- If a server admin becomes dishonest, anyone can host a replica server with
little work or effort. Dishonest in this case is not exclusive to abuse/corruption,
but includes anything that put's his/her own personal interest above the player's
interest.
- The server can outlive the server admin. If the operator of the server no longer
wishes to host the server, another can take over the project with relative ease.
- Anyone can contribute to the code-base of the project. Want to see a feature added?
Write the code yourself or find someone else who will- updates are not dependent on
the admin doing work. 
- Everything is a open forum and nobody (not even the admin) has veto power. If
the admin goes against the community, he/she risks a forked version of the server
poaching his/her playerbase. 
- Don't know how to code? If you have an idea make an issue/suggestion on the 
GitHub repository and it will be debated. If someone who can code likes it,
a pull-request will be made and voted on by the community.
- Bugs will be alleviated significantly faster and security will be far 
better. Things will be caught earlier and code will be under far more
scrutiny. Fixes are not reliant on a single developer. Code is reviewed
by far more people.
- Full transparency- nothing is hidden.

A fair counter claim: “Won’t this split the player base between multiple servers?”
It is possible, yes. Although it requires significant consideration from players to switch to a forked server. If the original server admin stays honest and has the longest track record of honesty, there should be no reason for players to make the change. Under copyleft licensing, all forks must also be open-source; this means that there will have to be a highly controversial and consequential feature with close to a 50-50 split for the community to splinter. In almost every instance that this has occurred with other open-source software, a single implementation regains majority usage eventually and the other becomes obsolete. To reiterate, it is highly unlikely that a forked host will overtake the original host unless the admins act against the community’s interest.

Players must demand that all new servers they play are held to this new 
golden standard. Failure will result in a repeat of history,
where server owners act in self-interest and slowly destroy the game.


Game Worth Playing
-
Now that we've addressed the underlying issue plaguing Factions, we can begin
to outline a game that stems from Factions circa 2014., taking only the
fundamental concepts and making the rest up as we go. 

### Economy

People quit Mineage after they got raided for a very simple reason. Because
after they built their massive base, there was nothing left to do.
Players only have the motivation to trench, gen, and do all these other
extremely repetitive tasks once. There is no incentive to keep playing
since players are not competing for anything. This does not just apply to
players in large, competitive factions, but extends to all players.

Naturally, Factions servers over the past 8 years have solved this problem
with payouts and short seasons. This is not sustainable as it only serves to
alienate new/casual players. Real-tangible "payouts" need to be available
to all players at all stages of the game to keep players playing.

In the past, payouts have paled in comparison to the amount of money that
is spent by a Faction to win.
It is utterly unprofitable and unrewarding to
competitively play Factions. The solution: “pot prizes” where all
store proceeds will go 75% towards funding the F-Top pot and
25% towards server operational costs. This is the only way to maximize
payouts for a competitive game without the server admin taking on
any exorbitant financial risk. The pot is paid out weekly to the top
13 factions (25% to 1, 15% to 2, 10% to 3, 5% to 4-13). The pot
is paid out evenly between all Faction members; this stops competitive
factions from recruiting too many members since payout amounts are
divided (casual factions can still recruit as many as they want).
Early game players likely won’t be able to just jump directly to
late game by joining a competitive faction, since they can inside 
and will take an equal portion of payouts.


With the introduction of a pot system, the admin’s risk for charge-backs and fraud becomes unacceptable. This is a primary reason why previous attempts have not been successful. Below is an excerpt from the Bitcoin white paper explaining the primary issue Bitcoin addresses.

> Commerce on the Internet has come to rely almost exclusively on financial institutions serving as trusted third parties to process electronic payments. While the system works well enough for most transactions, it still suffers from the inherent weaknesses of the trust based model. Completely non-reversible transactions are not really possible, since financial institutions cannot avoid mediating disputes. The cost of mediation increases transaction costs, limiting the minimum practical transaction size and cutting off the possibility for small casual transactions, and there is a broader cost in the loss of ability to make non-reversible payments for non- reversible services. With the possibility of reversal, the need for trust spreads. Merchants must be wary of their customers, hassling them for more information than they would otherwise need. A certain percentage of fraud is accepted as unavoidable. These costs and payment uncertainties can be avoided in person by using physical currency, but no mechanism exists to make payments over a communications channel without a trusted party.

Satoshi Nakamoto, 2008 (https://bitcoin.org/bitcoin.pdf)

Bitcoin solves this problem. However, Bitcoin by itself is not a pragmatic solution to replace traditional finance (PayPal/Credit Card checkout) due to Blockchain transaction fees and long confirmation times. It is necessary to use a layer 2 solution that builds on top of Bitcoin’s blockchain to solve Bitcoin’s scaling problem. Here is the problem as described in Lightning Network’s white paper:

> The payment network Visa achieved 47,000 peak transactions per second (tps) on its network during the 2013 holidays[2], and currently averages hundreds of millions per day. Currently, Bitcoin supports less than 7 transactions per second with a 1 megabyte block limit. If we use an average of 300 bytes per bitcoin transaction and assumed unlimited block sizes, an equivalent capacity to peak Visa transaction volume of 47,000/tps would be nearly 8 gigabytes per Bitcoin block, every ten minutes on average. Continuously, that would be over 400 terabytes of data per year. Clearly, achieving Visa-like capacity on the Bitcoin network isn’t feasible today.
> 
> To achieve much higher than 47,000 transactions per second using Bitcoin requires conducting transactions off the Bitcoin blockchain itself. It would be even better if the bitcoin network supported a near-unlimited number of transactions per second with extremely low fees for micropayments. Many micropayments can be sent sequentially between two parties to enable any size of payments.
> 
> While it is possible to scale at a small level, it is absolutely not possible to handle a large amount of micropayments on the [Bitcoin on-chain] network or to encompass all global transactions.

Joseph Poon and Thaddeus Dryja, 2016 (https://lightning.network/lightning-network-paper.pdf)

Lightning Network is a viable solution to alleviate the risks of fraud and charge-backs associated with traditional finance. Lightning Network is instant, pragmatic, and secure with 8 years of network/technology maturity.

The first, most obvious concern is, “How will players get Bitcoin via lightning network?”
It’s a very simple process. For U.S players, it’s a few clicks away in CashApp. For both U.S and European players, Strike, like cash app works seamlessly to convert fiat currency to BTC and send via lightning network. Players can also opt to use traditional exchanges (Binance, Coinbase, Kraken, Bitfinex, OKX) since they all support sending BTC via lightning network. For players who cannot KYC, there are unregulated/uninsured/foreign exchanges that are viable for small amounts (low-risk): https://github.com/theDavidCoen/LightningExchanges

The second concern, “What will I do with Bitcoin on lightning network once I withdraw funds from the server?”
Once again, it’s fairly simple. For those who can KYC in the U.S, you can simply just send the funds back to a CashApp account and it will automatically convert to USD. For both U.S and Europe, you can convert it back to USD easily on Strike and all traditional exchanges. For those who aren’t able to KYC, you can spend it very easily on gift-cards for DoorDash, Amazon, Visa, and more via FoldApp/Bitrefill.

This system transfers the burden of fraud/charge-back protection from the server admin to the player. The effects of using real-world currency within the server will also have far-reaching impacts and implications. To name some:

- Trickle-down economy from the F-Top winners (there are 13 factions actually making money playing the server)
- Poorer players can earn real money playing and sell items/services to wealthier players.
- Circulation of unobtainable items (cosmetic / novelty) originally auctioned off by admin (for BTC) hold re-sell value.
- Since all items (spawners / gear / etc) can be auctioned for both in-game money and BTC, it’s possible for someone to pay their way to the top. However, since payouts are structured in a weekly top-13 format, it’s unlikely they will adversely impact the competitive landscape. It’s expected for factions in F-Top to fall and rise since bases are raided and the map does not reset. It may make sense economically to spend some money to win high F-Top payouts. However, spending more money than you win / getting raided can cause financial burden. This is real economics. All transactions are final.

### In-game Economy

Now that we've addressed the underlying incentive systems,
we can begin to start balancing the economy.

There are 2 “currencies” in game. Points and bits.
You can either put your Points toward your
Faction’s F-Top value (cannot take them back out) or sell them for bits on
the Auction house. This promotes a trickle-down economy where the top
Factions that earn F-Top pot will trade bits for points. Points can also be
obtained through supply drops, crates, events, and selling mob/farm drops.
A bit is 1/1,000,000 of a Bitcoin.

The server is oriented around crates. Crates are the only way to get
spawners/non-vanilla items. There are 4 crates: Vote, Daily, Weekly,
Monthly, and Mythic. All crates can be re-rolled infinite times for
a fee (bits). The first four are self explanatory and will vary in
rewards levels. Players can purchase Mythic key-all (1 for all online
players), Mythic key-all + 5 (1 for all online + 5 more for self),
or Mythic key-all + 10 (1 for all online + 10 more for self). This
will incentivize players to stay online and will let them earn bits
by selling the items they get from crates in auction house.

Kits can also be purchased from the server using bits. Potion kit,
Builder kit, PvP kit (p4), and other vanilla obtainable kits are purchasable
using bits. These kits can also be rolled from crates.

There will be 1 "rank" that runs on a weekly subscription. This rank will
allow players to make sell-notes worth more than 100K points. This encourages
a sort of pay-to-play system for competitive players who want to compete
at F-Top pot. This should help bolster F-Top pot size while not hurting
casual play. It will also offer some cosmetic features like ability to
change name-color in chat/tab.

Purchasing weekly rank, kits, Mythic Crate key-alls, and crate re-rolls
are the
only times players will pay bits to the server. Combined, these will
contribute 75% to F-Top pot and 25% to operation costs. F-Top payouts
are the only time bits will ever be from the server to a player. This
makes the economy fair and sustainable. It also incentivizes players
to keep spawners placed since F-Top is not determined on the amount
of spawners placed at end of week, but by points from selling the
drops. This is not pay-2-win and with the trickle-down economy,
every player has ample opportunity to actually make real money
(even without spending any).

The game promotes a lot of player-player transactions through auction house
or private trading and is fully sustainable since the server admin takes
on no financial risk. This thoroughly addresses the issue of keeping all 
players incentivized. From this point, we can now focus on how to make the
game most engaging and fun for players. If this was not addressed first,
not even the most engaging game would be sustainable.

### Map
To truly stem off of "Golden Age" Factions, we must
 branch far enough away from current Factions to ensure current "meta" does
not impact our game. 

Foremost, while cannons and buffers are
seen as a pillar of Factions, removing cannon based play is the only way to
truly break away from current meta. As someone who got their start in
2016 Factions, this is not an easy decision to make; we all have great
memories making noob cannons and regen walls back in the day;
however, it is a necessary concession. 

The map size is 30K x 30K and will never reset. A best effort should
be made to keep the server up to date with the latest version of Minecraft.

Upon first login, players are spawned in the wilderness
with a horse and a starter kit. This horse respawns and is tied to the player.


The map is softly divided into four quadrants, separating 
early game and late game players. All new players spawn in Q1 and 
move to Q4 as they progress. Factions are be encouraged to move their bases whilst
progressing through the game. These zones do not have any “hard” impact
on gameplay. Players can travel freely. 

There are 4 sell locations, 1 located 5000 blocks from (0,0) in each quadrant of
the map (++/-+/--/+-). Example: Sell Location A in Q1 at (2500, 2500). Players
sell farm/mob-grinder drops at these locations. By making late-game
drops (ie: iron / IG drops) only sellable at Q4 and early-game
drops (ie: rotten flesh / Zombie drops) only sellable at Q1, it softly seperates
players. There is no enforcement against late game players sitting at
Q1 sell locations farm killing new players, other than it provides no real
economic benefit for the late game player and is wasting time. The sell
location in the your respective quadrant is way-pointed for Lunar Client users.

Supply drops will spawn in each of the 4 quadrants. The rewards of these
supply drops are proportional to the quadrant it is located in. The
supply drop coordinates will only be announced to players currently
in the relevant quadrant. This will discourage late game players from
bothering with Q1 supply drops. The timers for each quadrant supply
drops are synchronized (4 supply drops at the same time). Server-wide
events (Envoys / KOTH) can be held in the middle of the map and are
announced to everyone. For Lunar Client users, all events are way-pointed
for the duration of the event.


Although map borders may be very
large, it is unlikely that players will want to travel
far to sell items and participate in (0, 0) events. Players will naturally
want to move their base as they progress to
particpate in better supply drops and be closer to better sell locations. If
a late-game player does not move his/her base, it does not really matter
since they still have to travel to their proper sell location and still won't
really bother early-game players.
 
There is no teleporting what-so-ever. There is no PvP protected area in the
entire map. The only build protected area is sell locations and warzone
at (0,0).

Players will be able to toggle their name-tag. Allies/Faction
members will have a green player-outline to make them noticeable. Enemies
inside warzone will have red player-outlines. Shulkers, elytra, and
other game-altering items may be disabled (enable/disable based on
community vote or necessity). The nether and end are disabled
(can be enabled later on).

### Faction Play
Players can create bases anywhere, and claim up to X blocks for their faction.
These are not full-chunk claims, but region cube claims designated by claim wands.
For Lunar Client users,
a way-point is set at the center of this region.
Claims are only grief protected when all members of the faction have been
offline for more than 30 minutes. When a Faction member is online or in the
30 minute buffer period, anyone can break/place blocks in claimed regions.
Grief protection includes TnT protection.

Players should hide their claimed bases so others do not randomly
stumble across grief protected land while they are offline.
Claims are not shown on a map,
but claimed area cannot be over-claimed by other claims. All claimed area
must be connected. Bases underground are protected by Ray-trace Anti-Xray
technology, and are
expected to become “meta.” Players can disable name-tags so no passerby
on ground level should be able to detect your base unless they followed you or
you left hints to your base exposed.

In the center of every claim, a diamond block (indestructible) is spawned.
When right-clicked by a faction member, this block is used to convert items
to sell notes. When an enemy right-clicks the block inside your claim, he will
take 50% of your Faction value (cooldown 24 hours). 

In order to not restrict the amount of items a player can sell, sell-notes
will be used to convert items to a piece of paper with the same worth
(sellable at sell locations). Sell-notes worth more than 100K will force
a nametag on your head with the sell-note worth. Sell-notes cannot be
placed inside ender chests or put into horse-chests.

Conclusion
-
Competitive play should not come at the expense of casual play. Competitive play, when implemented correctly will actually bolster the casual experience. Competitive players are likely to spend more time on the server, deposit their own Bitcoin on the server, and become greatly invested in the server. Competitive players, who compete to win F-Top payouts, will likely reinvest their earnings towards winning the following week since payouts will grow as the server grows. Reinvesting will require those players to either purchase items from other players off auction house or purchase crate keys (all crate key purchases execute a key-all). Either way, the casual player is benefited by the competitive player. With the use of the quadrant system, late-game/competitive players are unlikely to bother early game/casual players in PvP or outposts. Just like Factions in 2016, the casual experience was amazing while the competitive scene was still present. At the end of the day, the point of Factions is to compete with other Factions; I don’t agree with the narrative that chaotic/reputation based factions is sustainable. After a certain point, every factions player tries to compete by either joining a Faction or forming one. It is necessary to make the beginner experience fun, to hook the player; but equally necessary to incentivize late-game play once a player gets over that hump. The only feasible way to sustain play is through competition with other factions.

It may help to initially circulate Bitcoin into the economy for voting just to help it get the economy going.

Technical
-

### Backend Bitcoin/Lightning Software
The server uses LNBits software to create a wallet for each user upon login. Funds held in LNBits wallets are ultimately in the custody of the server admin. It is HIGHLY recommended to only transfer funds into LNBits wallet when you are planning to use those funds. Funds received (from players or payouts) should also be immediately transferred out of LNBits wallet. The server in this capacity should act solely as a smart-contract enforcer for BTC <-> Minecraft Item transactions (player <-> player / player <-> admin). If players decide to hold funds in admin-controlled LNBits wallet, the admin is not liable for lost funds and funds are not regulated/insured. There are dozens of available custodial and non-custodial wallets available for Bitcoin Lightning Network. These are very easy to use and install on mobile & desktop. Withdrawals and deposits to and from these wallets is instantaneous and has very little fee associated. There is no excuse/reason to be holding funds within the LNBits wallet. However, there will not be a limit imposed on wallet funds in case a player wishes to make a larger transaction on the server.

### LNBits In-Game Interface
The in-game interface for LNBits wallet. Will also be integrated into auction-house, and “/trade”.

> “/btc pay <username> <amount>”
> 
> Pay another player a certain amount

> “/btc pay <bolt11 invoice>”
>
> Generate an invoice on an external wallet and pay into it from here. It is your responsibility to decode the invoice and verify the amount invoiced. There are websites and CLI tools for this.

> “/btc createinvoice <amount>”
> 
>Create an invoice to transfer funds into your LNBits wallet from an external source. This will generate a code that you can put into CashApp, Strike, Coinbase, YourExternalLightningWallet, etc. to transfer funds in.


> “/btc balance”
> 
> Check your LNBits wallet balance.


> “/btc payments”
>
> Get a list of all payments
