---
title: Trading at the Speed of Light
author: Donald MacKenzie
year: 2021
isbn: 9780691211381
---

## 1: introduction
- 8 - originally thought HFT used a lot of ML for complex data stuff, but most important signals are simple + well-known, so speed decides profit
- 12 - engineers have to unlearn CS education, cannot "safely abstract away from the physicality of the hardware on which his algorithms run" - "not an abstract information processor, but a material assemblage of plastic, metal, and silicon"
- 13 - algorithm isn't just recipe, it's specific language running on specific hardware
- 16 - in politics, things that are always important to other fields only become sporadically important
- 21 - incumbent exchanges profit from speed races by charging for connections, data
- 21 - philippon: no clear tendency for finance's iefficiency to increase from 1880s-2012
- 25 - 3 main signals: price movements in futures, order book balance, price movements on other exchanges
- 27 - "Liquidity, for example, is "sticky," in the sense that once traders expect a trading venue oto be the most liquid, it tends to remain so because they direct their trades there."

## 2: to the towers
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

## 3: "we'll show you our book. why won't they?"
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

## 4: dealers, clients, and the politics of market structure
- 107 - treasurys market largely dealer-client market - send IM or call on phone to buy
- 109 - nice table of market structure of instruments
- 110 - treasurys 65% dealer-intermediated (makes sense that fed is dealer of last resort. market is dominated by dealers)

## things to look up
- 14 - john law, annemarie mol 2008 on material politics
- 16 - pierre bourdieu, neil fligstein on fields
- 16 - andrew abbott on ecologies
- 20 - mackenzie 2019 on dark pools
- 21 - thomas philippon 2015 on financial efficiency
