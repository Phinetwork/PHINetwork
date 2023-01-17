---
description: >-
  For using any of the contracts, leave the referral and disclosure that the
  contract has been created by PHI Network, even if you make alterations and
  changes.
---

# Real Estate Mortgage Bridge

<pre class="language-solidity"><code class="lang-solidity">// // SPDX-License-Identifier: MIT
// Contract by PHI Network.

<strong>pragma solidity ^0.5.0;
</strong>contract MortgageAgreement { address payable public borrower; address payable public lender; uint256 public principal; uint256 public interestRate; uint256 public repaymentPeriod;

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
function isValid() public view returns (bool) {
    // Add code to check if the mortgage agreement is valid
    return true; // or false depending on the result of the check
}
}

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
function isValid() public view returns (bool) {
    // Add code to check if the mortgage agreement is valid
    return true; // or false depending on the result of the check
}
function execute() public {
    // Add code to execute the real estate transaction
    buyer.transfer(purchasePrice);
}
}
contract BridgeContract { MortgageAgreement mortgage; RealEstateTransaction realEstateTransaction;

constructor(address _mortgage, address _realEstateTransaction) public {
    mortgage = MortgageAgreement(_mortgage);
    realEstateTransaction = RealEstateTransaction(_realEstateTransaction);
}

function executeTransaction() public {
    // Check that all conditions for the mortgage and real estate transaction are met
    require(mortgage.isValid());
    require(realEstateTransaction.isValid());
    // Execute mortgage agreement
    mortgage.execute();
    // Execute real estate transaction
    realEstateTransaction.execute();
}
} 
</code></pre>
