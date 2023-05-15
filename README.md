# Smart Contract Auditor Learning Roadmap Step by Step in 2023
## A. Prerequisites
### 1) Learn Basic Programming
- [FreeCodeCamp JavaScript Course](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#basic-javascript)

### 2) Blockchain Basics
- [Blockchain 101 + BTC & ETH Whitepaper](https://youtube.com/playlist?list=PL5hZ7cADAJkdIVAcINQdsnfRTZZj6hjwB)
- [Ethereum Book](https://github.com/ethereumbook/ethereumbook)
- [Patrick Collins 32 hours FreeCodeCamp Course on YT](https://youtu.be/gyMwXuJrbJQ) (learn just Blockchain Basics section)

## B. Main
### 3) CTFs and Solidity (recommend to do theory+practice at once)
- [Patrick Collins 32 hours FreeCodeCamp Course on YT](https://youtu.be/gyMwXuJrbJQ) (learn Solidity + Hardhat section)
- [Solidity to the point](https://www.rareskills.io/learn-solidity)
  - Exercise: https://github.com/rareSkills/solidity-exercises
- [Solidity by example](https://solidity-by-example.org/)
- Foundry
  - Docs: https://book.getfoundry.sh/
  - Youtube: https://youtube.com/playlist?list=PLO5VPQH6OWdUrKEWPF07CSuVm3T99DQki
- CTFs:
  - [Damn Vulnerable Defi](https://www.damnvulnerabledefi.xyz/)
  - [Ethernaut](https://ethernaut.openzeppelin.com/)
    - Youtube: [D-Squared Ethernaut Playlist](https://youtube.com/playlist?list=PLiAoBT74VLnmRIPZGg4F36fH3BjQ5fLnz)
  - [Capture The Ether](https://capturetheether.com/)
 
### 4) Defi & Finance Basics
- DeFi:
  > Reference: https://teachyourselfcrypto.com/ (DeFi Section)
  - Token Contracts (Found on CTFs & Patrick Collins 32-Hours course video above)
    - Refer to: [CMichel Guide](https://cmichel.io/how-to-become-a-smart-contract-auditor/)
  - Proxies (Found on CTFs above)
    - Refer to: [CMichel Guide](https://cmichel.io/how-to-become-a-smart-contract-auditor/)
  - Masterchef 
    - Refer to: [CMichel Guide](https://cmichel.io/how-to-become-a-smart-contract-auditor/), [Synthetix Staking Rewards Contracts on YT](https://youtube.com/playlist?list=PL6dfW2OxzxT8mnis1je1WkIfknlaKt2vj)
  - Compound
    - Refer to: [CMichel Guide](https://cmichel.io/how-to-become-a-smart-contract-auditor/)
  - Uniswap V2
    - Refer to: [CMichel Guide](https://cmichel.io/how-to-become-a-smart-contract-auditor/)
- Finance:
  - [Learn Options, Swaps, Futures, MBSs, CDOs, Other futures derivatives on Khan Academy](https://www.khanacademy.org/economics-finance-domain/core-finance/derivative-securities)

### 5) Understanding Audits & Reports
  - Secureum Bootcamp:
     - Youtube: [D-Squared Secureum Bootcamp Playlist](https://youtube.com/playlist?list=PLiAoBT74VLnmK3Kc188fL37aviYjXeaPc)
     - Text: [Secureum Mindmap](https://github.com/x676f64/secureum-mind_map)
  - Past audit reports:
      - [C4](https://code4rena.com/reports)
      - [Solodit](https://solodit.xyz/)
      - [Sherlock](https://app.sherlock.xyz/audits/contests) ("finished" section)
  
    Learn based on priority, from:
      - Low risk, non critical issues and gas audits
      - High and medium risk findings (duplicate)
      - High and medium risk findings (unique)
  - Common Issues:
    > Reference: https://consensys.github.io/smart-contract-best-practices/attacks/
    
     - General Issues: 
        - https://twitter.com/KKat7531/status/1643710428470452225
        - https://github.com/FattahArrasyid/SC-Audit-Roadmap/blob/main/img01.jpg (No.8-12, 15-24)
     - High risk issues (by 0x52):
        - https://twitter.com/IAm0x52/status/1649420594855723010


### 6) Participate in contest:
  - [C4](https://code4rena.com/) 
  - [Sherlock](https://www.sherlock.xyz/)
  - [ImmuneFi](https://immunefi.com/)

### 7) Keep Learning

## Bonus
### My Personal Audit Tools:
  - IDE: VsCode + audit extension ("solidity visual developer" extension)
  - Framework: Hardhat/Foundry (Smart Contract Framework
  - Notetaking app: Notion (Mostly to get CLOC of the codebase, and sort it by the amount of CLOC)

### Audit Process:
  - [Tincho (Damn Vulnerable Defi CTF creator) audit process](https://youtu.be/A-T9F0anN1E)
  - [Patrick Collins audit process](https://youtu.be/TmZ8gH-toX0)

### Another Audit Learning Core Points: 
  - https://twitter.com/cryptostaker22/status/1653856172611612673
