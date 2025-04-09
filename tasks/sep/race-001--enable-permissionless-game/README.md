# Deputy Guardian - Enable Permissioness Dispute Game

Status: CONTINGENCY TASK, SIGN AS NEEDED

## Objective

This task updates the `respectedGameType` in the `OptimismPortalProxy` to `CANNON`, enabling users to permissionlessly propose outputs as well as for anyone to participate in the dispute of these proposals. This action requires all in-progress withdrawals to be re-proven against a new `FaultDisputeGame` that was created after this update occurs.

The batch will be executed on chain ID `11155111`, and contains `1` transactions.

## Tx #1: Update `respectedGameType` in the `OptimismPortalProxy`

Updates the `respectedGameType` to `CANNON` in the `OptimismPortalProxy`, enabling permissionless proposals and challenging.

**Function Signature:** `setRespectedGameType(address,uint32)`

**To:** `0x4220C5deD9dC2C8a8366e684B098094790C72d3c`

**Value:** `0 WEI`

**Raw Input Data:** `0xa1155ed9000000000000000000000000<OptimismPortalProxyAddress------------>0000000000000000000000000000000000000000000000000000000000000000`

### Inputs

**\_gameType:** `0` (`CANNON`)

**\_portal:** `0xF2891fc6819CDd6BD9221874619BB03A6277d72A`

### State Validations

Please see the instructions for [validation](./VALIDATION.md).
