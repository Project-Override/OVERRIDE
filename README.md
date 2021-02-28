***Description of Project (Override the Voting System)***

This project serves as a proof of concept for a government disintermediation and polling smart contract. We utilize two 21 day contract timelines under the Federal Rules of Civil Procedure and a 3 day recission period for a complete 45 day escrow period. Upon successful polling volume targets being met - NFTs are minted at the end of the 45 day escrow period. The NFTs represent a successful poll and store of perception within specific geographic regions. From the escrow state account the NFTs are sent to the accounts that represent those geographic regions to create a historical record of the perception of the public participating in the poll.

Within the first 21 day polling period Chainlink extracts/scrapes off-chain data from Twitter. When a specific 3-word-combination is found within a tweet a token is minted (once per twitter account; per 21 day polling period) and sent to the escrow state account. These tokens continue to accumulate within the escrow state account until the target polling volume is met. The tokens serve as a running tally of YAYs and NAYs for a specific proposal or sentiment. If the target polling volume is NOT met the tokens are burned. If the target polling volume is acheived the tokens are sent to the accounts that represent those geographic regions as a running tally for the second 21 day pollng period. This process repeats for the second 21 day polling period. Upon absence of a polling volume to override the previous two polling periods the NFTs minted are now sent to the location accounts per geographic region.

***Chainlink Integration***

Scrape Twitter for keyword-combination within 21 day vesting period. Keyword-combination Trigger/Broadcast MINT of token. When target amount of tokens MINTED met: Trigger/Broadcast Smart Contract to SEND Tokens to LOCATION accounts. This re-occurs for 2nd 21 day vesting period and 3rd 3 day vesting period. Upon Completion all Tokens Burned or Tokens and NFTs are sent to corresponding location (Owners') Accounts.

***Quorum Functionality***

45 Day Vesting Schedule. ***First 21 Day Vesting Period***: If QUORUM (Token Quota) NOT met Burn Tokens on 21st Day. If QUORUM met MINT tokens and SEND digital assets from ESCROW account to location account. Proceed to ***Second 21 Day Vesting Period***. If QUORUM (Token Quota) NOT met Burn Tokens on 42nd Day. If QUORUM met MINT tokens and SEND digital assets from ESCROW account to location accou. If 'Override Switch' Quota NOT met AFTER ***3 Day Vesting Period***: Disburse NFTs from ESCROW to location Accounts.

***Escrow Override Switch***

Day 45: Burn NFTs (If 90% Token Quota met: burn NFTs). If Quota not met disburse NFTs from ESCROW to location Accounts.


***POS Voluntary Tax Deferral (Override the Taxation System)***

Send Transaction to Merchant with Tax Percentage held in ESCROW account. Multisig Control connected to QUOURM Feature-set which disburses to Merchant control or flows into Community ESCROW account.

![Solana Proof of Concept Design](https://user-images.githubusercontent.com/77212309/109435370-0f7d6780-79cf-11eb-943a-c536ee62a8fb.jpg)
