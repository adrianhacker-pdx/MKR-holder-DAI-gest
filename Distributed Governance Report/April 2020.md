# MakerDAO

Greetings from the MakerDAO ecosystem. My name is Adrian Hacker, and I contribute to the MakerDAO platform as a community development participant and governance participant. I report back to the governance community a weekly summary of events as well as work with the governance community around public relations issues. I will expand upon that later. 

In the age of information, literacy, and liability allow me to do some quick legalese housekeeping: I will be contributing to the Distributed Governance Report, the happenings of MakerDAO governance. Unless otherwise specified, I am not the direct, authoritative voice of MakerDAO Governance as a whole. My thoughts and opinions are my own and may not necessarily reflect that of the entire Governance Community. I do have other governance members Q.A. my writing. I do strive to keep my writing free of editorial opinion and 100% fact-based unless otherwise noted. I am not a MakerDAO foundation member; therefore, the statements made by me do not reflect that of the MakerDAO foundation. All of that being said, the Governance and Foundation community, thus far, have seemed pleased with my journalistic methods. 

Allow me to introduce you to the MakerDAO platform and give you a small tour of the "what's" and "who's."

Products of MakerDAO include: 

* Multi-collateral Dai: a stable coin that is designed to be price pegged to the equivalence of $1 U.S.
* [Oasis DeFi Platform:](https://oasis.app)
* Lock Dai into a savings account with a very generous interest rate (usually around 7-8%)
* Exchange Dai / Eth / Wrapped Bitcoin / PAX / TUSD / BAT / REP and others
* Borrow Dai by locking collateral such as Eth, BAT, or USDC into a vault
* Maker token: Holders can lock this token into a smart contract allowing them to vote. Maker is a fungible token that can be exchanged or held elsewhere
* Collateral Auctions: Eth, BAT, or USDC auctioned at a slight discount to ensure debt does not go uncollateralized
* Debt Auctions: Maker auctioned at a slight discount to reconcile uncollateralized system debt

DAO stands for "decentralized autonomous organization." MakerDAO consists of the MakerDAO Foundation, MakerDAO Governance, and the MakerDAO Community. These are the major stakeholders. To further clarify the roles of these stakeholders: 

* The Foundation is the business organization that created MakerDAO and is incrementally handing off the operations to governance. 
* Governance is the community of persons that hold a token known as Maker. A Maker holder can create, vote upon, and implement by sufficient vote, MakerDAO system-wide policy. 
* Community would be those individuals that participate in the financial products offered by MakerDAO or an organization offering a Dai third-party derivative. Dai holders and vault owners are direct community stakeholders. [These Dai variants](https://medium.com/bzxnetwork/a-tour-of-the-varieties-of-dai-9ff155f7666c) are minted by way of Dai but functionally operated by other organizations. These derivatives do get affected by MakerDAO monetary policies; therefore, they can be considered third-party community stakeholders.

There is a lot to know about MakerDAO and how it works. To learn further about MakerDAO check out [MakerDAO.com](https://makerdao.com) or visit [Awesome MakerDAO](https://awesome.makerdao.com/#faqs)

# Signaling: Discussions and Community

The [MakerDAO Forum](https://forum.makerdao.com/) is where governance signaling begins by posting or commenting on issues. Issues that gain traction are then moved on to an [On Chain Poll](https://vote.makerdao.com/polling) where Maker holders vote to gain a soft consensus. A [weekly governance and risk](https://www.youtube.com/channel/UC4jqZlzQHUhzqf5rMd5ywTw/videos) call is conducted via Zoom Meetings. This meeting is intended for discussion and debate, not final decision making. Forum issues are brought here to be discussed further as well as issues from the foundation which require governance approval. Visit any of these links for more detailed and up to date information.

## Black Thursday March 12th Governance and Risk Call

Cryptocurrency price drops happening the week of March 12th caused an ERC-20 blockchain congestion, which prevented timely oracle price updates from happening in addition to increased Gas costs for auction bidding. While the full event is under investigation, this allowed for a single auction bidder to bid on and win collateral auctions that happened en mass from the price drop, for zero to very low Dai bids. This system exploit caused an uncollateralized system debt totaling around 6 million Dai. Vault owners that were liquidated by way of a zero Dai bid incurred a loss that was greater than the debt they owed. Discussions are happening around whether or not to compensate vault owners. The system debt is being reconciled by way of Maker token being minted and sold for Dai (debt auction). The foundation has developers and outside consulting firms working on analyzing and understanding exactly how the exploit happened. Overall state of the platform is healthy, as mechanisms were in place for this contingency. 

## New Collateral Type Added: USDC

Following the market price drops, Dai demand increased sharply. Investor fear led to the transfer of volatile assets to Dai. Dai liquidity dropped such that a new collateral was needed to allow for the minting of new Dai for bidding on the debt auctions. Maker holders approved the addition of the USDC stable coin, by Circle, as a new collateral type. The controversy surrounding this comes from the fact that USDC is a regulated cryptocurrency. Regulation is contradictory to the decentralization principle. The biggest risk of this collateral type is that Circle can and will blacklist any address that has been identified for money laundering, terrorist funding, and all other U.S. financial security infractions. The USDC collateral gets held in a single address smart contract adapter; therefore, the wrong-doings of one USDC holder could ultimately lock up and invalidate the entire value of this collateral for MakerDAO. Monetary policy with this collateral type is being set to incentivize auction bidding, but not for other investment strategies. Governance is actively looking at other stable coin options. Up to date information can be found in the forums as this issue is evolving quickly.

## Technical Bug Causes Debt Auctions to Hang

A bug was discovered in the smart contract for debt auctions, which is considered minor. About 20 debt auctions totaling around 1.1 million Dai entered a state that caused them to hang and not enter the active bidding phase. This bug was able to be overridden by a governance spell being initiated and activated by vote.

## Full Control of the Maker Token turned over to Governance

Until recently, only the foundation was able to mint or burn Maker token. These are the high-level functions that ultimately determine monetary policy, including Maker inflation and overall system financial stability. This last week the full authority of minting and burning the Maker token is transferred to the governance community to control. This is a huge step for the platform in the incremental steps towards full decentralization. Opinion: Keeping on track with decentralization, even during times of uncertain price and system exploit, sets an amazing precedent for this platform to handle the day-to-day operation and the unforeseen without fear. 

## Governance Public Relations

Following the high profile events of the last month, the governance community has identified the need for a framework around authoritative DAO communications. DeFi, by nature, holds a lot of information in different online arenas. Competent, accessible, consistent, and factual communication has been identified as a necessity by MakerDAO governance. A group of governance team members has been formed to draft some policy or best-known methods to present for governance to evaluate for implementation.

## Emergency Shutdown Consortium Being Formed

The governance community has an emergency shutdown option available that will halt and freeze the operation of the entire system in the event of an unforeseen extreme event. Recent events have identified the need to identify thresholds and triggers to be created very specifically around the use of such a tool. Clear identification of the stakeholders that this is meant to protect is the existential question around the matter. Then step by step procedure for activating an emergency shut down will be developed, followed by the step by step procedure for system redeployment following an emergency shutdown. Right now, the governance community is interested in finding third-party Dai derivative stakeholders to have a seat or two in this consortium. The deliverable will be a proposal for the governance community to vote upon for official emergency shutdown policy.

## SCD (Sai) Shutdown

The governance community is preparing to shutdown and reconcile the global supply of single collateral Dai (Sai) in the upcoming months. Technical consideration and procedures have been presented in a draft form. Debt ceilings are being lowered for Sai such that the supply can no longer grow. Anyone holding Sai is encouraged to convert to Dai at the [official migration site](https://migrate.makerdao.com), where Sai can quickly and easily be converted to Dai.

# [Live Votes and Proposals](https://vote.makerdao.com/)

After an issue has reached a soft consensus by polling or brought up for a vote in the weekly governance and risk call, it goes to an executive vote. Executive votes are continuous approval in which a vote will remain open until enough votes are reached for implementation. For system security, however, a spell will expire after a month of not achieving the approval threshold.

Executive votes often consist of evaluation and adjustment of monetary policy. Polling issues are often just monetary policy issues with the occasional policy or procedural change. For that reason, polling will not be presented here but can be researched further at vote.makerdao.com/polling

This is currently the only open executive vote:

* Adjust Multiple Risk Parameters:
* Lower the USDC Stability Fee from 20% to 16%
* Lower the Dai ETH Debt Ceiling by 10 million to 90 million Dai

Recent executive votes passed in the last 30 days:

* Unblock the remaining debt auctions
* Allows the stuck debt auctions to move forward for sale.

* Proposal for Collateral On-boarding of USDC 
* Allows users to open vaults with the USDC stable coin. 

* Adjust Multiple Risk Parameters
* Lower the Sai Stability Fee from 7.5% to 3.5%
* Lower the Dai Stability Fee 0.5% to 0%
* Keep the Dai Savings Rate Spread at 0%
* Note: This will set the DSR to 0%

* Executive Vote: Adjust Multiple Risk Parameters
* Lower the Sai Stability Fee 2% to 7.5%
* Lower the Dai Stability Fee 4% to 4%
* Keep the Dai Savings Rate Spread at 0%
* Note: This will set the DSR to 4%
* Lower the Migration Contract Debt Ceiling 20M to 10M
* Lower the SCD debt ceiling 5M to 25M
* Lower the MCD debt ceiling 50M to 100M
* Set the Global MCD debt ceiling 113M
* Raise the Flip auction TTL from 10 minutes to 6 hours
* Raise the Flip auction lot size from 50 ETH to 500 ETH
* Lower the Flip auction maximum duration from 3 days to 6 hours
* Raise the Flop auction TTL from 10 minutes to 6 hours
* Raise the Debt Auction Delay from 48 hours to 6.5 days

* Activate the Debt Ceiling Adjustments and Set the Dai Savings Rate Spread
* Lower the Sai Debt Ceiling by 5 million to 25 million Sai
* Lower the Dai ETH Debt Ceiling by 20 million to 130 million Dai
* Set the Dai Savings Rate Spread to 1%
* Note: This will set the DSR to 7%

# [Calendar and Meetings](https://calendar.google.com/calendar/embed?src=makerdao.com_3efhm2ghipksegl009ktniomdk@group.calendar.google.com&ctz=America/Los_Angeles&pli=1)

The heading link will take you to the official MakerDAO community event calendar. These are the recurring meetings of interest: 

## Community Meeting - Every Tuesday at 9:00 am PST

Meeting themes include: 

* Recent and upcoming events 
* Answer general questions
* Interview new team members
* Chat with special guests
* Demo new releases

Join Hangouts Meet
meet.google.com/idg-znme-kvt
Join by phone
‪+1 409-207-0104‬ PIN: ‪663 316‬#

## Governance and Risk Meeting - Every Thursday at 9:00 am PST

Meeting themes include: 

* Establish some base principles around Governance and Risk: what is, how it works, etc.
* Discuss the latest documents published by the Risk team
* Explore use-cases of specific aspects of the framework
* Introduce industry experts

https://zoom.us/j/697074715

One tap mobile

+19292056099,,697074715# U.S. (New York)
+16699006833,,697074715# U.S. (San Jose)

Dial by your location

+1 929 205 6099 US (New York)
+1 669 900 6833 US (San Jose)

Meeting ID: 697 074 715

Find your local number: https://zoom.us/u/acRbIMDvK 
