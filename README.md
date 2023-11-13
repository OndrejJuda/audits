# 0xJuda's Security Audits

## Contacts

Twitter: [@0xOndrejJuda](https://twitter.com/0xOndrejJuda)

Discord: 0xjuda

Contest / bug bounty platform profiles:

- [Code4rena](https://code4rena.com/@0xJuda)
- [CodeHawks](https://www.codehawks.com/profile/clkhuag2y0000ld08utph38va)

## All Time Stats

| Protocol                                                                             | Date           | Platform  | Rank | High | Medium | Low |
| ------------------------------------------------------------------------------------ | -------------- | --------- | ---- | ---- | ------ | --- |
| [Real Wagmi #2](https://github.com/OndrejJuda/audits#real-wagmi-2)                   | October 2023   | Sherlock  | 8    | 2    | 0      | -   |
| [Venus Prime](https://github.com/OndrejJuda/audits#venus-prime)                      | September 2023 | Code4rena | x    | 0    | 0      | 0   |
| [Centrifuge](https://github.com/OndrejJuda/audits#centrifuge)                        | September 2023 | Code4rena | x    | 0    | 0      | 0   |
| [Chainlink Staking v0.2](https://github.com/OndrejJuda/audits#chainlink-staking-v02) | September 2023 | Code4rena | ?    | ?    | ?      | ?   |
| [Tokemak](https://github.com/OndrejJuda/audits#tokemak)                              | August 2023    | Sherlock  | ?    | ?    | ?      | -   |
| [CodeHawks Escrow](https://github.com/OndrejJuda/audits#codehawks-escrow)            | July 2023      | CodeHawks | 7    | 0    | 3      | 1   |
| [Beedle](https://github.com/OndrejJuda/audits#beedle)                                | July 2023      | CodeHawks | 151  | 2    | 1      | 0   |
| [Unitas Protocol](https://github.com/OndrejJuda/audits#unitas-protocol)              | June 2023      | Sherlock  | 12   | 0    | 1      | -   |

## October 2023

### Real Wagmi #2

Contest link: [sherlock.xyz](https://audits.sherlock.xyz/contests/118)

Repository: [github.com/sherlock-audit/2023-10-real-wagmi](https://github.com/sherlock-audit/2023-10-real-wagmi)

| ID                                                                                                   | Title                                                                                                       | Severity |
| ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-10-Real-Wagmi-2/H-01.md) | Slippage protection for LiquidityBorrowingManager#repay doesn't work                                        | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-10-Real-Wagmi-2/H-02.md) | Lender burning his position makes complete repay of borrow position impossible                              | High     |

## September 2023

### Venus Prime

Contest link: [code4rena.com](https://code4rena.com/contests/2023-09-venus)

Repository: [https://github.com/code-423n4/2023-09-venus](https://github.com/code-423n4/2023-09-venus)

### Centrifuge

Contest link: [code4rena.com](https://code4rena.com/contests/2023-09-centrifuge)

Repository: [github.com/code-423n4/2023-09-centrifuge](https://github.com/code-423n4/2023-09-centrifuge)

### [Work In Progress] Chainlink Staking v0.2

Contest link: [code4rena.com](https://code4rena.com/contests/2023-08-chainlink-staking-v02)

Repository: [github.com/code-423n4/2023-08-chainlink](https://github.com/code-423n4/2023-08-chainlink)

## August 2023

### [Work In Progress] Tokemak

Contest link: [sherlock.xyz](https://audits.sherlock.xyz/contests/101)

Repository: [github.com/sherlock-audit/2023-06-tokemak](https://github.com/sherlock-audit/2023-06-tokemak)

## July 2023

### CodeHawks Escrow

Contest link: [codehawks.com](https://www.codehawks.com/contests/cljyfxlc40003jq082s0wemya)

Repository: [github.com/Cyfrin/2023-07-escrow](https://github.com/Cyfrin/2023-07-escrow)

| ID                                                                                             | Title                                                             | Severity |
| ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------- |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-01.md) | ResolveDispute can revert because of rebase token                 | Medium   |
| [M-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-02.md) | No methods to stop and replace arbiter if keys are leaked         | Medium   |
| [M-03](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-03.md) | Tokens get stuck in Escrow when arbiter or seller are blacklisted | Medium   |
| [L-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/L-01.md) | There is no check that arbiter is not buyer nor seller            | Low      |

### Beedle

Contest link: [codehawks.com](https://www.codehawks.com/contests/clkbo1fa20009jr08nyyf9wbx)

Repository: [github.com/Cyfrin/2023-07-beedle](https://github.com/Cyfrin/2023-07-beedle)

| ID                                                                                             | Title                                                                            | Severity |
| ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/H-01.md) | Malicious lender gains value by borrowing from his pool and giving the loan away | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/H-02.md) | Function sellProfits lack expiration timestamp and slippage protection           | High     |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/M-01.md) | Uniswap fee is hardcoded in Fees.sol                                             | Medium   |

## June 2023

### Unitas Protocol

Contest link: [sherlock.xyz](https://app.sherlock.xyz/audits/contests/73)

Repository: [github.com/2023-04-unitasprotocol-judging](https://github.com/sherlock-audit/2023-04-unitasprotocol-judging)

| ID                                                                                            | Title                                                    | Severity |
| --------------------------------------------------------------------------------------------- | -------------------------------------------------------- | -------- |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-06-Unitas/M-01.md) | Stale price leads to user getting incorrect token amount | Medium   |
