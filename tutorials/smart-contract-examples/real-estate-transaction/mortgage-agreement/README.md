---
description: >-
  For using any of the contracts, leave the referral and disclosure that the
  contract has been created by PHI Network, even if you make alterations and
  changes.
---

# Mortgage Agreement

```solidity
// // SPDX-License-Identifier: MIT
// Contract by PHI Network.

pragma solidity ^0.5.0;
contract MortgageAgreement { address payable public borrower; address payable public lender; uint256 public principal; uint256 public interestRate; uint256 public repaymentPeriod;
constructor(address payable _borrower, address payable _lender, uint256 _principal, uint256 _interestRate, uint256 _repaymentPeriod) public {
    borrower = _borrower;
    lender = _lender;
    principal = _principal;
    interestRate = _interestRate;
    repaymentPeriod = _repaymentPeriod;
}

function execute() public {
    require(!borrower.send(principal));
    uint256 interest = principal * interestRate * repaymentPeriod / 12;
    require(!lender.send(interest));
}
}
```
