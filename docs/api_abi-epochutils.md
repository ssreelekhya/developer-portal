---
id: API_ABI-EpochUtils
title: EpochUtils
---
[//]: # (tagline)
# contract EpochUtils
is [IEpochUtils](api_abi-iepochutils.md)
imports SafeMath, [IEpochUtils](api_abi-iepochutils.md)

*Source*: [EpochUtils.sol](https://github.com/KyberNetwork/smart-contracts/blob/master/contracts/sol6/Dao/EpochUtils.sol)
___

## INDEX

<AUTOGENERATED_TABLE_OF_CONTENTS>

## REFERENCE

### Functions

### `getCurrentEpochNumber`
Returns the current epoch number.
___
function __getCurrentEpochNumber__() public view override returns (uint256)\
**Returns:**\
Current epoch number

<br />
 
### `getEpochNumber`
Returns the epoch number at timestamp.
___
function __getEpochNumber__(uint256 timestamp) public view override returns (uint256)
| Parameter | Type  | Description |
| --------- |:-----:|:-----------:|
| `timestamp` | uint256 | timestamp in epoch time    |
**Returns:**\
Epoch number at timestamp 
