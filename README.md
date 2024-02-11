# 0xJuda's Security Audits

## Contacts

Twitter: [@0xOndrejJuda](https://twitter.com/0xOndrejJuda)

Discord: 0xjuda

Contest / bug bounty platform profiles:

- [Code4rena](https://code4rena.com/@0xJuda)
- [CodeHawks](https://www.codehawks.com/profile/clkhuag2y0000ld08utph38va)
- [Sherlock](https://audits.sherlock.xyz/watson/0xJuda)

## All Time Stats

| Date           | Protocol                                                                             | Platform  | High | Medium | Low |
| -------------- | ------------------------------------------------------------------------------------ | --------- | ---- | ------ | --- |
| November 2023  | [Morpho Blue](https://github.com/OndrejJuda/audits#morpho-blue)                      | Cantina   | ?    | ?      | ?   |
| November 2023  | [NextGen](https://github.com/OndrejJuda/audits#nextgen)                              | Code4rena | 3    | 1      | 0   |
| October 2023   | [Real Wagmi #2](https://github.com/OndrejJuda/audits#real-wagmi-2)                   | Sherlock  | 2    | 0      | -   |
| September 2023 | [Venus Prime](https://github.com/OndrejJuda/audits#venus-prime)                      | Code4rena | 0    | 0      | 0   |
| September 2023 | [Centrifuge](https://github.com/OndrejJuda/audits#centrifuge)                        | Code4rena | 0    | 0      | 0   |
| September 2023 | [Chainlink Staking v0.2](https://github.com/OndrejJuda/audits#chainlink-staking-v02) | Code4rena | 0    | 0      | 0   |
| August 2023    | [Tokemak](https://github.com/OndrejJuda/audits#tokemak)                              | Sherlock  | 4    | 0      | -   |
| July 2023      | [CodeHawks Escrow](https://github.com/OndrejJuda/audits#codehawks-escrow)            | CodeHawks | 0    | 3      | 1   |
| July 2023      | [Beedle](https://github.com/OndrejJuda/audits#beedle)                                | CodeHawks | 2    | 1      | 0   |
| June 2023      | [Real Wagmi](https://github.com/OndrejJuda/audits#real-wagmi)                        | Sherlock  | 0    | 0      | -   |
| June 2023      | [Unitas Protocol](https://github.com/OndrejJuda/audits#unitas-protocol)              | Sherlock  | 0    | 1      | -   |
| Summary        | 11                                                                                   |           | 11   | 6      | 1   |

## November 2023

### [Work In Progress] Morpho Blue

Morpho Blue is a trustless lending primitive that offers unparalleled efficiency and flexibility. It enables the creation of isolated lending markets by specifying any loan asset, any collateral asset, a liquidation LTV (LLTV), an oracle, and an interest rate model.

Contest link: [cantina.xyz](https://cantina.xyz/competitions/d86b7f95-e574-4092-8ea2-78dcac2f54f1)

### NextGen

Advanced smart contracts for launching generative art projects on Ethereum.

Contest link: [code4rena.com](https://code4rena.com/contests/2023-10-nextgen)

Repository: [https://github.com/code-423n4/2023-10-nextgen](https://github.com/code-423n4/2023-10-nextgen)

| ID                                                                                              | Title                                                                                                                        | Severity |
| ----------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/code4rena/2023-10-NextGen/H-01.md) | Bids will be stuck in the auction contract if the winner doesn't implement onERC721Received                                  | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/code4rena/2023-10-NextGen/H-02.md) | Active bidder may reenter into cancelBid from claimAuction to profit at the expense of the contract and original token owner | High     |
| [H-03](https://github.com/OndrejJuda/audits/blob/main/audits/code4rena/2023-10-NextGen/H-03.md) | Hacker can DoS auction and gas grief claimAuction caller                                                                     | High     |
| [H-04](https://github.com/OndrejJuda/audits/blob/main/audits/code4rena/2023-10-NextGen/H-04.md) | User can mint more tokens than he should during the allowlist phase                                                          | High     |

## October 2023

### Real Wagmi #2

Unlock the power of DeFi with Wagmi - an all-in-one platform for trading, liquidity provision, swapping, and yield strategy generation.

Contest link: [sherlock.xyz](https://audits.sherlock.xyz/contests/118)

| ID                                                                                                  | Title                                                                          | Severity |
| --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------ | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-10-Real-Wagmi-2/H-01.md) | Slippage protection for LiquidityBorrowingManager#repay doesn't work           | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-10-Real-Wagmi-2/H-02.md) | Lender burning his position makes complete repay of borrow position impossible | High     |

## September 2023

### Venus Prime

Earn, borrow & lend on the #1 Decentralized Money Market on the BNB chain.

Contest link: [code4rena.com](https://code4rena.com/contests/2023-09-venus-prime)

### Centrifuge

The institutional ecosystem for on-chain credit.

Contest link: [code4rena.com](https://code4rena.com/contests/2023-09-centrifuge)

### Chainlink Staking v0.2

A security mechanism in which stakers commit LINK in smart contracts to back certain performance guarantees around oracle services.

Contest link: [code4rena.com](https://code4rena.com/contests/2023-08-chainlink-staking-v02)

## August 2023

### Tokemak

Generating sustainable liquidity for the tokenized world. Eliminating inefficiencies and helping LPs to deploy liquidity where it can do the most work is exactly why the Tokemak v2 is built.

Contest link: [sherlock.xyz](https://audits.sherlock.xyz/contests/101)

| ID                                                                                             | Title                                                                | Severity |
| ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-08-Tokemak/H-01.md) | User can transfer LMPVault shares to claim rewards multiple times    | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-08-Tokemak/H-02.md) | Router double accounting problem and exposed funds in smart contract | High     |
| [H-03](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-08-Tokemak/H-03.md) | Liquidations miss delegate call to swapper                           | High     |
| [H-04](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-08-Tokemak/H-04.md) | User can deposit and immediatelly withdraw to steal rewards          | High     |

## July 2023

### CodeHawks Escrow

This project is meant to enable smart contract auditors (sellers) and smart contract protocols looking for audits (buyers) to connect using a credibly neutral option, with optional arbitration.

Contest link: [codehawks.com](https://www.codehawks.com/contests/cljyfxlc40003jq082s0wemya)

| ID                                                                                             | Title                                                             | Severity |
| ---------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- | -------- |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-01.md) | ResolveDispute can revert because of rebase token                 | Medium   |
| [M-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-02.md) | No methods to stop and replace arbiter if keys are leaked         | Medium   |
| [M-03](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/M-03.md) | Tokens get stuck in Escrow when arbiter or seller are blacklisted | Medium   |
| [L-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Escrow/L-01.md) | There is no check that arbiter is not buyer nor seller            | Low      |

### Beedle

Oracle free peer to peer perpetual lending.

Contest link: [codehawks.com](https://www.codehawks.com/contests/clkbo1fa20009jr08nyyf9wbx)

| ID                                                                                             | Title                                                                            | Severity |
| ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------- |
| [H-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/H-01.md) | Malicious lender gains value by borrowing from his pool and giving the loan away | High     |
| [H-02](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/H-02.md) | Function sellProfits lack expiration timestamp and slippage protection           | High     |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/codehawks/2023-07-Beedle/M-01.md) | Uniswap fee is hardcoded in Fees.sol                                             | Medium   |

## June 2023

### Real Wagmi

Swap earn and provide liquidity on the leading decentralized protocol built on zkSync. Experience the future of decentralized finance with Wagmi.

Contest link: [sherlock.xyz](https://audits.sherlock.xyz/contests/88)

### Unitas Protocol

Unitized stablecoins serving as units of account representing emerging market currencies. A new currency revolution.

Contest link: [sherlock.xyz](https://app.sherlock.xyz/audits/contests/73)

| ID                                                                                            | Title                                                    | Severity |
| --------------------------------------------------------------------------------------------- | -------------------------------------------------------- | -------- |
| [M-01](https://github.com/OndrejJuda/audits/blob/main/audits/sherlock/2023-06-Unitas/M-01.md) | Stale price leads to user getting incorrect token amount | Medium   |
