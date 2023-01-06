# President

```solidity
pragma solidity ^0.5.11;

contract ArticleTwo {
  // President and Vice President
  struct President {
    string name;
    uint256 term;
  }
  struct VicePresident {
    string name;
    uint256 term;
  }
  President p;
  VicePresident vp;

  // Election process
  function electPresident(string memory _name) public {
    p.name = _name;
    p.term = 4;
  }
  function electVicePresident(string memory _name) public {
    vp.name = _name;
    vp.term = 4;
  }

  // Constructor
  constructor() public {
    p.name = "";
    vp.name = "";
  }
}

```
