# AresAudits - Portfolio

Welcome to my GitHub portfolio! I am a dedicated Smart Contract Security Researcher with a strong focus on ensuring the safety and reliability of decentralized applications. This repository showcases my work, contributions, and research in the field of smart contract security.

## 🛡️ About Me

I'm a dedicated and detail-oriented Smart Contract Security Researcher with a deep passion for DeFi and Web3 security. My expertise lies in identifying critical vulnerabilities, mitigating complex risks, and ensuring the integrity and safety of blockchain protocols. I have a proven track record in both private security audits and competitive auditing.

## 🏆 Audit Competition Rankings  

| Contest Name        | Platform    | Rank      |
|---------------------|-------------|-----------|
| Kleros cross chain | Hats Finance | [1st](https://app.hats.finance/audit-competitions/cross-chain-realitio-proxy-0x9efc47be23fb612aff9bce511bad4a308f1f4f39/leaderboard) | 
| Tapioca           | Hats Finance   | [1st](https://app.hats.finance/audit-competitions/tapioca-0xe0b920d38a0900af3bab7ff0ca0af554129f54ad/leaderboard)     |
| DAOsis           | Hats Finance    | [3rd](https://app.hats.finance/audit-competitions/daosis-0x8ef21ecb2af12ce9cc0e475eec25f90a9622b4f4/leaderboard)     |
| Palmera           | Hats Finance| [4th](https://app.hats.finance/audit-competitions/palmera-0x5fee7541ddcd51ba9f4af606f87b2c42eea655be/leaderboard)     |
| Illuminex            | Hats Finance   | [5th](https://app.hats.finance/audit-competitions/illuminex-0x0bb4aa1f58719707405c231fcdf0b405714799cf/leaderboard)    |
| Aligned-Layer            | Cantina    | [6th](https://cantina.xyz/competitions/781d30df-39a9-47e6-b290-e388c79e04ea/leaderboard)     |
| Interpol           | Cantina| [8th](https://cantina.xyz/competitions/55023131-27df-44e4-af46-bec298d0fa8e/leaderboard)     |
| Fenix            | Hats Finance   | [8th](https://app.hats.finance/audit-competitions/fenix-0x9d7765a7ebd5b6322a30797a44a5428531970d3d/leaderboard)     |

&More...


## 🔒 Private Audits  

| Protocol Name       | Protocol Type   | Report        | Date       |
|---------------------|-----------------|---------------|------------|
| Rdatadao           | DAO            | [upcoming]     | Aug 2025  |
| Nebula | NFT Marketplace | [upcoming]     | Aug 2025   |
| World3.ai | Dapp | [Link](https://hashlock.com/wp-content/uploads/2025/08/World3ai-Updates-Smart-Contract-Audit-Report-Final-Report-v1.pdf)   | July 2025  |
| Levva | Defi | Confidential | Aug 2025 |
| Theoriq | Defi | Confidential | July 2025 | 
| World3.ai | Defi | [Link](https://hashlock.com/wp-content/uploads/2025/08/World3.ai-Smart-Contract-Audit-Report-Final-Report-v1.pdf) | July 2025 |
| OpenZK | Defi | [Link](https://hashlock.com/wp-content/uploads/2025/01/OpenZK-8th-Smart-Contract-Audit-Report-Final-Report-v3.pdf) | June 2025 | 
| Defi-Bull | Defi | [Link](https://hashlock.com/wp-content/uploads/2025/03/DeFi-Bull-4th-Smart-Contract-Audit-Report-Final-Report-v1.pdf) | June 2025 |
| Potomac Capital | SToken |Confidential| July 2025 | 
| Allbridge | Defi | Confidential | July 2025 |
| HoneyPot finance | Defi | Confidential | May 2025 |
| DB Cherry | AA Wallet | [Link](https://hashlock.com/wp-content/uploads/2025/05/DB-Cherry-Smart-Contract-Audit-Report-Final-Report-v1.pdf) |  May 2025 |
| Defi-Bull | Defi | [Link](https://hashlock.com/wp-content/uploads/2025/03/Defi-Bull-World-2nd-Smart-Contract-Audit-Report-Final-Report-v3.pdf) | May 2025 |
| Cove | Defi | [Link](https://github.com/pashov/audits/blob/master/team/pdf/Cove-security-review_2025-04-16.pdf) | April 2025 |
| Metaversal | Defi | [Link](https://hashlock.com/wp-content/uploads/2025/03/Metaversal-Smart-Contract-Audit-Report-Final-Report.pdf) | March 2025 | 
| Immersve | CeDefi | [Link](https://hashlock.com/wp-content/uploads/2024/08/Immersve-2nd-Smart-Contract-Audit-Report-Final-Report-v3.pdf) | March 2025 |


## 🚀 Findings

**Note:** This portfolio is not up-to-date.

|Platform       | Title                     | Severity   | Link
--------------  | ------------------------- | ---------- | -------------------------------------
| [CodeHawks](https://codehawks.cyfrin.io/) | Allowance issue in transfer function | High | [Link](https://codehawks.cyfrin.io/c/2024-08-tadle/s/1552)
|  | AuthorityRate can be bypassed | High | [Link](https://codehawks.cyfrin.io/c/2024-08-tadle/s/1716)
|  | Reentrancy in withdraw() function | High | [Link](https://codehawks.cyfrin.io/c/2024-08-tadle/s/1672)
|  | Platform Fees Can Be Bypassed for Low Decimal Standard ERC20 Tokens | Medium | [Link](https://codehawks.cyfrin.io/c/2024-08-tadle/s/1706)
|  | EIP712MetaTransaction.executeMetaTransaction() failed txs are open to replay attacks | Medium | [Link](https://codehawks.cyfrin.io/c/2024-11-one-world/s/836)
| [Cantina](https://cantina.xyz/) | Incorrect Fee Share is Applied to Overridden Referrers in Beekeeper::distributeFees() | High | private
|  | Missing Expiration Check in HoneyLocker::withdrawERC721() and withdrawERC1155() | High | private
|[BugRap](https://bugrap.io/)   | By staking very small amount of tokens,attacker steals the user funds and here user gets 0 shares in return         | High       | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Bugrap/donation_attack.md)
|                               | WAVAX rewards or native tokens or eth will be permanently locked in YieldSource Contract  | Medium | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Bugrap/emergency_withdraw.md)
|               | Precision loss in _calculateBoxPrice() function leads to loss of funds | Medium | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Bugrap/precision_loss.md)
|[HackenProof](https://hackenproof.com/) | Incorrect Utilization Rate Calculation Leads to Inaccurate Borrow Rate in getBorrowRate() Function | High     |[Link](https://github.com/AresAudits/Portfolio/blob/main/reports/HackenProof/Incorrect_UR.md)
|[Hats Finance](https://hats.finance/security-researchers) | Bypass of isSafe Validation Allows Malicious Contract Registrations and Spam the Palmera Module contracts with System-Wide Exploitation | High   | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Hats/Bypass.md)
|               | Potential Vulnerability in execTransactionOnBehalf Function Allowing Destruction of targetSafe contract | Medium | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Hats/Destruction_of_targetSafe.md)
|  | Inadequate Verification of safe Address in _executeModuleTransaction Function Leading to Potential Execution of Malicious Contracts | High | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Hats/Inadequate_Verification.md)
|  | Signature Malleability in WebAuthn.sol | Medium | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Hats/Signature_Malleability.md)
|  | User tokens will be fully vested before the duration,incorrect logic implementation | Medium | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Hats/incorrect_logic.md)
|  | ProcessAndSortSignatures Function Fails to Handle Multiple Valid Signatures for Owners, Leading to Reversions in checkNSignatures Function if Threshold is Greater Than 1 | Medium | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Hats/palmera.md)
|[Sherlock](https://www.sherlock.xyz/)   | Improper Validation in depositEth Function Allows Bypassing of Pool Type Checks which allow Direct Manipulation of Dai Holdings         | Medium     | [Link](https://github.com/AresAudits/Portfolio/blob/main/reports/Sherlock/Improper_Validation.md)
|  | Incorrect Handling of Fee-on-Transfer Tokens in ManagedBudget | Medium | [Link](https://github.com/sherlock-audit/2024-06-boost-aa-wallet-judging/issues/394)
|  | Approval Race Condition for USDT Token | Medium | [Link](https://github.com/sherlock-audit/2024-08-sentiment-v2-judging/issues/593)
| [Immunefi](https://immunefi.com/) | Unprotected Zero Amount Check in VaultV2::depositQuote() Allows Free 1e18 share Minting | High | private

## ⚡ Skills & Tech Stack  

**Languages:** Solidity, Rust, Javascript, Go, C, C++  
**Frameworks & Tools:** Foundry, Hardhat, Echidna, Slither, React, Woke

## 🌐 Connect with Me
Feel free to reach out to me through:
- **[Twitter](https://x.com/_AresAudits)**
- **[Email](aresaudits@gmail.com)**
- **[Telegram](https://t.me/Nishant_323)**
- **[Discord](http://discordapp.com/users/1047907939647762442)**

---
