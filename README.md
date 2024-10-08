# AresAudits - Portfolio

Welcome to my GitHub portfolio! I am a dedicated Smart Contract Security Researcher with a strong focus on ensuring the safety and reliability of decentralized applications. This repository showcases my work, contributions, and research in the field of smart contract security.

## 🛡️ About Me

I am passionate about blockchain technology, cryptography, and secure coding practices. My expertise includes conducting comprehensive security audits, developing security tools, and participating in audit competitions.

## 🌐 Connect with Me
Feel free to reach out to me through:
- **[Twitter](https://x.com/_AresAudits)**
- **[Email](aresaudits@gmail.com)**
- **[Telegram](https://t.me/Nishant_323)**
- **[Discord](https://discord.gg/AGaRdjgD)**

## 🚀 Findings


|Platform       | Title                     | Severity   | Link
--------------  | ------------------------- | ---------- | -------------------------------------
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




---
