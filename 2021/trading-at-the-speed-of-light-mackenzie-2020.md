---
title: Trading at the Speed of Light
author: Donald MacKenzie
year: 2021
isbn: 9780691211381
---

## 1. introduction
- 8 - originally thought HFT used a lot of ML for complex data stuff, but most important signals are simple + well-known, so speed decides profit
- 12 - engineers have to unlearn CS education, cannot "safely abstract away from the physicality of the hardware on which his algorithms run" - "not an abstract information processor, but a material assemblage of plastic, metal, and silicon"
- 13 - algorithm isn't just recipe, it's specific language running on specific hardware
- 16 - in politics, things that are always important to other fields only become sporadically important
- 21 - incumbent exchanges profit from speed races by charging for connections, data
- 21 - philippon: no clear tendency for finance's iefficiency to increase from 1880s-2012
- 25 - 3 main signals: price movements in futures, order book balance, price movements on other exchanges
- 27 - "Liquidity, for example, is "sticky," in the sense that once traders expect a trading venue oto be the most liquid, it tends to remain so because they direct their trades there."

## 2. to the towers
- 33 - futures traders switched from commodities to financial products bc the skill that mattered most was understanding trading pit dynamics
- 37 - bucket shops were gambling venues to wager on instrument prices
- 38 - food price inflation happened in 70s, so political rewards came up for intervening in trading w/ regulation
- 40 - futures venue leader leo melamed saw opportunity in being regulated - would "legitimatize what we were doing. Anyone that has a federal agency over it is a legitimate thing. You don't have a federal agency over gambling."
- 41 - advocated for new regulator CFTC that was not the SEC
- 42 - CFTC jurisdiction intentionally vague - "Without mentioning futures on share indexes explicitly – that overt intrusion into its domain would certainly have sparked SEC opposition"
- 43 - sp500 futures simple, cheap, easy to short - these advantages meant sp500 futures tended to move before underlying shares (1984-85 as much as 20-45 mins)
- 45 - trading was personal, reciprocity mattered between traders, reputation everything
- 50 - early system aurora showed each individual trader, let traders choose who to do business with; a real pit simulation, couldn't be in more than one virtual pit at a time
- 53 - globex system was not social market like aurora, but abstract, anonymous
- 63 - futures lead bc liquidity: is sticky and price changes tend to show up in most liquid venues vs less liquid. also bc leverage.
- 64 - futures' ag roots -> CFTC reports to senate ag committe vs SEC senate banking committee. ag committee donations comes from financial sector. totally arbitrary but wont change because entrenched interests
- 65 - signals in hft not from just inherent nature of systems or economics but from political processes "They also reflect political process – Melamed's grasphing of the opportunity provided by Poage's wish to protect his committee's jurisdiction; Johnson's crucial 20-word addition to the relevant law; and so on – and the outcomes of the conflicts that those processes involve. Althrough those conflicts may now be long past, some of their outcomes continue to structure today's world of automated trading in profound ways."

## 3. "we'll show you our book. why won't they?"
- 71 - consolidated order book was proposed - "single, centralized, nationwide order book" - CLOB
- 77 - trading shares via big banks was more expensive than instinet but came with other benefits like meetings with investment targets, IPO allocation, research reports, subsidized travel, straight up cash
- 79 - dealers' role in nasdaq trading meant they had info that couldn't be deduced from instinet, so human traders could be more predictive than algos
- 80 - SEC made dealers to fill orders on screens after a crash where they didn't
- 83 - biggest dealers didn't just make markets but also handled orders from institutional investors - nasdaq had non-anonymous bids on screen so you could deduce dealers' private info
- 88 - early hft "sharply aware of computing's materiality" - cache, main memory, storage differences
- 89 - island reused recently canceled order slots bc that record would be in cache and much faster than making a new one
- 89 - island streamed out order book changes to all systems, had each do its own order book reconstruction
- 94 - dealers front ran orders in 1993, avoided odd-eights price quotes to keep spreads wide
- 96 - reg NMS stopped trading floor prices from special protection, electronic orders didn't have to wait for people
- 96 - by early 2000s, trading venues needed hft firms to keep volume up
- 97 - main signals in hft:
    1. futures lead
    2. order-book dynamics: changes in balance of bid/offers
    3. fragmentation: changes in order books for same shares on other venues 
    4. related instruments: changes in market of thing correlated with thing traded
- 97 - fragmentation wasn't a given - wouldn't exist if CLOB came into being
- 101 - in europe, venue allowed hft, and bid-ask spread dropped 50% and trading volume jumped much higher, became largest-volume trading venue

## 4. dealers, clients, and the politics of market structure
- 107 - treasurys market largely dealer-client market - send IM or call on phone to buy
- 109 - nice table of market structure of instruments
- 110 - treasurys 65% dealer-intermediated (makes sense that fed is dealer of last resort. market is dominated by dealers)
- 111 - interdealer brokers would provide screens with treasury prices but it was forbidden to show directly to clients. when RMJ securities did this in 80s, they lost all interdealer broker business, had to reverse course
- 113 - tradeweb respected dealer-client distinction, didnt require changes to process, was successful
- 114 - dealers didn't want clients to see client flow, wanted to make sure clients traded only via dealers not directly. in 2016 direct match tried to do this but never launched
- 117 - private bilateral trading means no risk of getting picked off by other hft, so can offer better prices in markets. hft careful not to exploit greater speed of their systems in these markets so they don't profit too much from biletaral partner
- 118 - treasury content w/ status quo of regulation of treasurys mkt, hard for SEC to act
- 119 - dept of treasury likes that banks compelled to bid on treasurys
- 119 - treasury doesn't want to rock the boat and weaken primary dealers bc they might not take on bidding obligations. hft has had to compromise w/ mkt structure instead of overthrowing it like in share trading
- 121 - banks act as primary dealers so they're not informally excluded from profitable govt business
- 122 - italy ministry of finance uncomfortable with non-banks bc they erode profit for banks, threaten banks' willingness to be primary dealers
- 124 - in 70s, returers made text messaging for dealers called 'conversational dealing'. let dealers converse and ask for price quotes. careful to emphasize did not do automated matching for bids and offers
- 127 - in forex, everyone exposed to default risk by trading partners, so calculate and limits extent of counterparty risk - "You have to compute and send a specific price for everybody. Everybody sees a different price."
- 131 - banks asked trading platforms to stop making its prices available for specific participant to execute against bc mad at hft making money on them
- 132 - very cool chart of hft signals and markets they apply to. crypto has order-book dynamics + fragmentation
- 133 - spoofing, entering fake bids/offers to fool algos, is banned
- 133 - no unified clearing + settlement for futures, so much harder for new venues to compete with incumbents (vs shares where central settlement meant easier to compete from the start)
- 133 - SEC permanent federal body, can piss people off. CFTC dependent on reauthorization so can't pursue policy that would generate opposition

## 5. "not only would i lose my job, i might lose my legs too!"
- 138 - good diagram of how trading systems communicate / interact
- 151 - repeater equipment waterproofed and put on top of towers to avoid wire distance from top to bottom. digital systems "were discarded in favor of the speed obtainable using simpler, purely analog repeaters"
- 154 - price in markets can be influenced by weather between chicago and new jersey
- 155 - banks got beaten on speed bc they didn't pay attention to fact that their orders were going through normal telecom data centers
- 157 - persico accepted less availability due to rain (95% instead of many 9s) bc using fewer antennas meant faster speed. better to be fastest than most available in hft
- 159 - "Rain has little effect on laser transmission, though fog is a major problem; millimeter wave is heavily disrupted by rain but not by fog." - so use both and get better availability
- 160 - literally more than $1m spent on lens coatings to resist bird droppings
- 168 - speculative triggering: "If, for example, a firm's system anticipates a price movement, it can start to send to the exchange's system a packet or series of packets encoding an order that responds to that movement. If, as it does so, no data containing evidence of the movement are received, the system can then kill the order, for example by simply ceasing to transmit, or, as DD puts it, by 'scrambl[ing] the checksum.' In either case, the exchange's system will treat the incoming packets as malformed or erroneous and discard them, meaning that no order is actually placed."
- 168 - leading futures exchanges afraid of getting overloaded by speculative triggering
- 169 - eurex doesn't want to ban, but has an ip address to discard to, so won't be processed

## 6. how hft algorithms interact, and how exchanges seek to influence it
- 178 - queue position matters a lot
- 178 - reg NMS connects markets virtually instead of by CLOB but implicitly assumes zero latency between exchanges
- 181 - intermarket sweep orders matter. bad for hft firms that can't use them. dunno why lol
- 182 - "Market-making algorithms ... often have to be ultrafast (and therefore not too complex), because of their need to be at or close to the ehad of the time-priority queue for execution and the danger fo their quotes becoming stale and being picked off"
- 184 - race between makers cancelling stale quotes and takers picking them off
- 184 - microwave links between chicago, nj used for picking off quotes above all else. When rain hit, picking off stopped, liquidity improved (in 2011-12)
- 185 - phase 2 after mckay bros link: when rains heavily, makers don't know if taker links have also failed, so makers have to widen spreads to decrease risk -> decreases liquidity
- 186 - sophisiticated trading algos identify others that are vulnerable like when approaching inventory limit (sounds like keynesian beauty contest dis-aggregated). taking from specific algo is most computationally expensive trading
- 188 - cat and mouse unusual
- 188 - market-impact trading: exploit likely influence of its own actions on other algos
- 189 - one tactic is to force other firm to cut losses - drive market down, force other algo to liquidate, buy those shares, sell for profit. potentially illegal
- 193 - easier to backtest taking strategies bc they work with existing order book. makers add to order book
- 195 - good to run making and taking in same shop if only to prevent makers from getting picked off - "Attempts to take ... had the unintended, emergent consequence of increasing the profitability of the firm's market-making algorithms. The latter would be to a degree protected from taking algorithms in the wider market by the fac t that one of the firm's own taking algorithms might well cause the cancellation of a making order before it could be picked off, and so its making algorithms would be 'run over' less often than would otherwise have been the case, boosting their profits." - great for makers, crappy for takers in firm bc increased maker profit, takers didn't see those good trades happen. there have to be better incentives lol. idk share the picked off ones? idk
- 199 - parfx disclosed counterparties after trade. banks could complain to parfx about hft firm but also to prime-broker bank that sponsored that hft
- 199 - parfx also randomized delivery latency of 
- 200 - reuters made system that delay taking by 3ms but not order cancels
- 201 - one way to encourage making is to pay for it. called rebates. "As rebates became more prevalent, they sparked controversy, with their critics suggesting, for example, that payments of this kind, which often were retained by brokers rather than being passed to their clients, could distort brokers' decisions as to where to send their clients' orders for execution... Nevertheless, this pricing strucutre – takers being charged fees, makers being given payments by the exchange – has become predominant in US share trading."

## 7. conclusion
- 219 - "A former regulator, interviewee RH (who was central to the formulation of those rules), told me that his approach to circumventing finance-sector opposition to SEC market-structure interventions 'was that if I wanted to achieve this' (making a hand gesture indicating a minor move), 'I would propose this' (making a gesture signaling a larger change).
- 225 - all things being equal, hft makes trading cheaper. but cheaper trading can have wider effects - more trading, fixation on short-term gains)
- 226 - probably worthwhile to mitigate hft speed races bc costs are borne by end investors

## things to look up
- 14 - john law, annemarie mol 2008 on material politics
- 16 - pierre bourdieu, neil fligstein on fields
- 16 - andrew abbott on ecologies
- 20 - mackenzie 2019 on dark pools
- 21 - thomas philippon 2015 on financial efficiency
- 116 - direct match treasurys market (failed to launch, opportunity?)
- 148 - laumonier 2019 on pilsov
- 184 - shkilko, sokolov 2016 on rain -> liquidity
- 201 - battalio, corwin, jennings 2016 on rebates
- 226 - budish et al 2016 on speed races
- 239 - durbin 2010 hft guide
