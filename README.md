# 0xJuda's Security Audits

## Contacts

Twitter: [@0xOndrejJuda](https://twitter.com/0xOndrejJuda)

Discord: 0xjuda

## All Time Stats

| Protocol                                                                  | Date        | Platform  | Rank    | High | Medium |
| ------------------------------------------------------------------------- | ----------- | --------- | ------- | ---- | ------ |
| [Tokemak](https://github.com/OndrejJuda/audits#tokemak)                   | August 2023 | Sherlock  | ?       | ?    | ?      |
| [CodeHawks Escrow](https://github.com/OndrejJuda/audits#codehawks-escrow) | July 2023   | CodeHawks | ?       | 1    | 3      |
| [Beedle](https://github.com/OndrejJuda/audits#beedle)                     | July 2023   | CodeHawks | ?       | 2    | 2      |
| [Unitas Protocol](https://github.com/OndrejJuda/audits#unitas-protocol)   | June 2023   | Sherlock  | 12      | 0    | 1      |

## July 2023

### CodeHawks Escrow

Contest link: [codehawks.com](https://www.codehawks.com/contests/cljyfxlc40003jq082s0wemya)

Repository: [github.com/Cyfrin/2023-07-escrow](https://github.com/Cyfrin/2023-07-escrow)

| ID                                                                                            | Title                                                              | Severity |
| --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/H-01.md) | There is no check that arbiter is not buyer nor seller            | High     |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-01.md) | ResolveDispute can revert because of rebase token                 | Medium   |
| [M-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-02.md) | No methods to stop and replace arbiter if keys are leaked         | Medium   |
| [M-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-03.md) | Tokens get stuck in Escrow when arbiter or seller are blacklisted | Medium   |

### Beedle

Contest link: [codehawks.com](https://www.codehawks.com/contests/clkbo1fa20009jr08nyyf9wbx)

Repository: [github.com/Cyfrin/2023-07-beedle](https://github.com/Cyfrin/2023-07-beedle)

| ID                                                                                             | Title                                                                            | Severity |
| ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/H-01.md) | Malicious lender can seize borrowers collateral by using fake token              | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/H-02.md) | Function sellProfits lack expiration timestamp and slippage protection           | High     |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/M-01.md) | Malicious lender gains value by borrowing from his pool and giving the loan away | Medium   |
| [M-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/M-02.md) | Uniswap fee is hardcoded in Fees.sol                                             | Medium   |

## June 2023

### Unitas Protocol

Contest link: [sherlock.xyz](https://app.sherlock.xyz/audits/contests/73)

Repository: [github.com/2023-04-unitasprotocol-judging](https://github.com/sherlock-audit/2023-04-unitasprotocol-judging)

| ID                                                                                            | Title                                                    | Severity |
| --------------------------------------------------------------------------------------------- | -------------------------------------------------------- | -------- |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-06-Unitas/M-01.md) | Stale price leads to user getting incorrect token amount | Medium   |