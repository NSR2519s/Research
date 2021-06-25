<h3 align="center">Research Template</h3>

---

## Table of Contents

- [Overview](#Overview)
- [Links](#Links)
- [Tokenomics](#Tokenomics)
- [Code Overview](#Code)
- [Team Members](#Team) 
- [Advisors & Early Backers](#Advisors)
- [Project Roadmap](#Roadmap)
- [Ecosystem & Network Effect](#Ecosystem)
- [Community Support](#Community)
- [Potential Competitors](#Competitors)
- [Problems and areas of concern](#Problems)
- [Final Verdict](#Verdict)

## Overview <a name = "Overview"></a>
  - Problem: SHORT: Privacy issues on Blockchain\
             LONG:  Public blockchains are precisely that: public. On the most popular block- chains of today, all of your on-chain activity is available for the                world to see, even a decade later. With on-chain analysis systems improving to a point where you are trivially traceable, this presents an obvious                  problem for the present day blockchain user, but it also presents a fundamental challenge for large-scale adoption. Imagine a world where paying for                your morning coffee tells the coffee shop, its barista, and its customers how much you have in your bank account, how much you get paid, and where                  else you spend your money.
             
  - Solution: RAILGUN is a collection of smart contracts (computer code that enforces rules and performs a task to fulfill transaction obligations in DeFi                         applications) that use zero-knowledge proofs (that is, certain things about entities). There are ways to prove them, without revealing what they are                 or sensitive details to them). These working together, Railgun makes it possible for users to exchange currencies and use apps in the DeFi space                     without having to link their origin addresses or other activity.
  
  - Technology: Railgun is composed of five functions:\
                1.  ADD transfers assets into RAILGUN and creates a new zero-knowledge note,representing all of the assets and their owner. This action is not in                   itself private(because it originates from outside the system, but it is the first step to creating privacy). The note is added to the live pool.\
                2.  REMOVE transfers assets from RAILGUN to an arbitrary address by destroying a note. Again, this is done in zero-knowl- edge, where the user                     proves ownership of the destroyed note without revealing the note or themselves. However, because the receiver is outside the system, this data                     will not be obscured.\
                3.  SPLIT turns one or more zero-knowl- edge notes into two zero-knowledge notes. The input notes are moved from the live pool to the dead pool,                   and the output notes are added to the live pool. All of this is done in zero-knowledge, where the user proves that they own the input notes, and                   that the input notes have not been used before, without revealing the note, or themselves. Splitting can be co-opted as a way to transfer funds, by                 setting a different owner in one of the newly created notes. This helps to hide the precise intent of the split.\
                4.  SWAP exchanges the ownership of two notes. All of this is done in zero-knowl- edge, keeping secret both the notes and the owners. Swapping can                 also be co-opted as a way to transfer funds, by exchanging a non-zero note for an empty note. This helps to hide the pre- cise intent of the                       split.\
                5.  ADAPT is a special composition of REMOVE and then ADD . It takes assets from RAILGUN, uses them to interact with another Ethereum smart                         contract, and then puts the resulting funds back into RAILGUN with the same owner, all in one onchain transaction. Although the type and amount of                 assets is neces- sarily revealed in order to interact with other applications, the owner is able to stay anonymous throughout the entire process,                   which preserves their overall privacy.\
                All actions will also come with varying levels of privacy and anonymity that the user can select to reduce gas costs where necessary. Users will                   also be able to batch multiple actions into one proof to reduce gas costs.  
                
  - Value Proposition: Privacy without the cost of sacrificing your preferred blockchain. And frankly cant stress the need of Privacy enough. It conceptualises the                        core principles and utility of having a blockchain in the first place.

  - Token Use Cases:  Users will be able to:

                      1.  Trading Darkpool Style Where No One Can Copy Your Farming Strategies
                      2.  Pay your attorney confidentially when seeking legal advice on personal disputes.
                      3.  Create a shielded balance without outsiders knowing the specifics of your diamond handbag
                      4.  Receive donations without outsiders being able to view donation history
                      5.  Prevent spying and data collection about their transactional habits
                      6.  Avoid being targeted by advertisers or fraudsters based on your DeFi habits
                      7.  Stop Watching Your DeFi Habits on Any Date Before You Have Dinner
  
## Links <a name = "Links"></a>
  - Website: [https://railgun.org/)
  - Whitepaper: [https://drive.google.com/file/d/1MW7YuDwCmsLVNfXyzmECPBZjykz9Rsnk/view?usp=sharing)
  - Github: [TBA)
  - Twitter: [https://twitter.com/railgun_project)
  - Telegram Announce: [https://t.me/railgunproject)
  - Telegram Community: [https://t.me/railgun_privacy)
  - CoinMarketCap: [N/A)
  - Block Explorer [N/A)

## Tokenomics <a name = "Tokenomics"></a>
  - Circulating Supply:
  - Total Supply:
  - Maximum Supply:
  - TGE Event Info:
  - Token Distribution:
  - Token Lockups:
  - Token Unlock Schedule:

## Code Overview <a name = "Code"></a>
  - Active developers: Emmanuel Goldstein (Check George Orwel's 1984),Kieran Mesquita  
  - Errors & Audits: Independent ABDK audit in progress. Will launch report soon.
  
## Team <a name = "Team"></a>
1. https://www.linkedin.com/in/emmanuel-goldstein-98489a20b/?originalSubdomain=au - Founder.
2. https://www.linkedin.com/in/kieran-mesquita/?originalSubdomain=au - Code Developer.
3. [Team Member 3's LinkedIn](https://www.linkedin.com) - Job title.

## Advisors & Early Backers <a name = "Advisors"></a>
  - Advisor: Edward F
  - Bring value to the project?

## Roadmap <a name = "Roadmap"></a>
1. Item 1. DAO 
2. Item 2. Integrate with Ethereum, PolyGun, BSC, Polkadot
3. Item 3. Mobile friendly UI in progress for Android and iOS
4. Item 4. Private Dex( Using Atomic Swaps)

## Ecosystem & Network Effect <a name = "Ecosystem"></a>
1. Item 1. Ethereum
2. Item 2. Polygon
3. Item 3. Polkadot

## Community Support <a name = "Community"></a>
- Community is extremely small and the product started development in 2020(imo). Telegram community size: 888, Twitter size: 4044, engagement: Decent.

## Potential Competitors <a name = "Competitors"></a>
- Website: https://scrt.network/
- Website: https://www.pantherprotocol.io
- Website: https://phala.network/

## Problems and areas of concerns<a name = "Problems"></a>
- Flag 1. 
- Flag 2.
- Flag 3.
- Flag 4.

## Final Verdict <a name = "Verdict"></a>
- Review.
