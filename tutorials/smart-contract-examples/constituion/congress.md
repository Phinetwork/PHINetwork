# Congress

```solidity
pragma solidity ^0.5.11;

contract Congress {
  // Legislative powers 
  enum LegislativePowers {
    Taxation, BorrowingMoney, RegulationCommerce, Naturalization, Bankruptcy, 
    CoinageRegulation, WeightsMeasures, PiraciesFelonies, WarPeace, ArmyNavy, 
    PostOffice, Patents, Copyrights
  }

  // Senate and House of Representatives
  struct Senate {
    uint8 seats;
    uint8 term;
  }
  struct HouseOfReps {
    uint8 seats;
    uint8 term;
  }
  Senate s;
  HouseOfReps h;

  // Constructor
  constructor(uint8 seats_senate, uint8 term_senate, uint8 seats_house, uint8 term_house) public {
        s.term = term_senate;
    h.seats = seats_house;
    h.term = term_house;
  }
}

```
