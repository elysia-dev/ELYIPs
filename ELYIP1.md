# Introduction

>- ELYIP#: 1
>- Title: Governance Vote on Introduction of Vault concept in BSC Mainnet Money Pool
>- Network: Binance Smart Chain 
>- Author: [won](https://forum.elyfi.world/u/won/summary)
>- Helper: [Jong](https://forum.elyfi.world/u/jong/summary)
>- Status: ELYIP Response
>- Date Created: 2022-01-17
>- Date Updated: 2022-01-17

# Short Summary
This proposal includes an improvement plan that can provide high deposit APY to investors depositing in the soon-to-open BSC network money pool.

# Paragraph Summary
The proposal for this governance vote is as follows.

1. To open BUSD money pool (BSC mainnet) with Vault concept applied
2. To agree to the proposed DeFi automatic operation policy
3. Maximum amount of DeFi automatic management: 5M USD (Additional voting is required to increase the maximum value of the automatic operation of DeFi.)

The deposit APY of ELYFI protocol can be increased by automatically investing virtual assets deposited in ELYFI money pool into other DeFi money pools. An example of DeFi is the Anchor Protocol on the Terra network.

It is expected that the target APY can be raised to a maximum of 10% through the automatic operation of DeFi. This can provide higher returns to the existing ELYFI users. In addition, the higher deposit APY compared to that of other DeFi will be an incentive to lead potential depositors to ELYFI money pool.

# Background Information
The ELYFI protocol provides deposit interest to money pool depositors through interest on loans that are currently secured by loan receivables. However, due to the nature of the DeFi protocol, it is not easy to generate a loan from the money pool in the beginning. In order to increase the initial protocol deposit, ELYFI is offering an attractive rate of return by paying ELFI tokens as rewards in addition to interest on the deposit. However, from the depositor's point of view, it is necessary to increase the deposit APY itself, which is the essence of the DeFi protocol, to create an incentive to invest in the long term.

The Elysia team introduces the Vault concept to the soon-to-be-opened BSC money pool, and proposes a way to increase ELYFI's deposit APY by automatically investing in other DeFis.

# Proposal details
### Vault Structure

The first money pool to be opened on the BSC mainnet is BUSD. We propose the following vault structure for the safety of fund management and the maximization of profits for investors.
![image](https://user-images.githubusercontent.com/90824532/150732833-380b9a11-947f-4941-aa36-20b957d221b1.png)



30% of the total amount of BUSD deposited by investors into the money pool is used for real estate collateral loans like the existing method, and 70% is used for automatic DeFi operation.

The schematic logic of DeFi automatic operation is as follows.

* BUSD loan from a lending company in Moneypool
* BUSD -> UST Swap (Pancakeswap)
* BSC UST -> Terra UST (Terra bridge)
* UST Staking (Anchor protocol)

### Target investment ratio and APY

The target investment ratio and target APY for each real estate mortgage and DeFi automatic investment sector of the lending company are as follows.
![Target](https://user-images.githubusercontent.com/90824532/150733883-038ff784-510b-4717-9f36-c52f53f25c99.png)




In other words, the target average APY of the lending company is 15.7%, and 3.2% is set for currency hedging and reserve storage. This will allow 12.5% of APY to go back to the money pool.

In consideration of liquidity, the target U value of the money pool is 0.8 (only 80% of the money pool supply is operated). Through this, the target **Deposit APY** returned to the depositors is 12.5% * 0.8 = **10%**.


### Comparison of Deposit APY(Supply APY) with other DeFis
*(as of 2022.01.17)*
![Comparison](https://user-images.githubusercontent.com/90824532/150733891-06797be8-a5e6-4fb5-b419-1f3cae502438.png)


### Others

**In addition to Deposit APY, Mining APY is also generated.** About 16,667 ELFI tokens are mined per day in the BUSD moneypool, which is distributed according to the share of Moneypool Supply.

## Reference
* [Elysia Medium](https://medium.com/elysia-magazine/governance-vote-on-introduction-of-vault-concept-in-bsc-mainnet-money-pool-c10549218f9b)
* [Anchor Protocol](https://www.anchorprotocol.com/)
