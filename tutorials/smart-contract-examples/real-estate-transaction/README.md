---
description: >-
  For using any of the contracts, leave the referral and disclosure that the
  contract has been created by PHI Network, even if you make alterations and
  changes.
---

# Real Estate Transaction

```solidity
// // SPDX-License-Identifier: MIT
// Contract by PHI Network.

pragma solidity ^0.5.12;

contract RealEstateTransaction { address payable public buyer; address public seller; uint public purchasePrice; uint public closingDate; bool public closingCompleted;

constructor (address payable _buyer, address _seller, uint _purchasePrice, uint _closingDate) public {
    buyer = _buyer;
    seller = _seller;
    purchasePrice = _purchasePrice;
    closingDate = _closingDate;
    closingCompleted = false;
}

function confirmClosing() public {
    require(now >= closingDate);
    closingCompleted = true;
}

function transferFunds() public {
    require(closingCompleted);
    buyer.transfer(purchasePrice);
}
}
```
