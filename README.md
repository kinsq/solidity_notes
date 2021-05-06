# solidity_notes
tutorial notes on solidity docs.
see https://docs.soliditylang.org/en/v0.8.0/

write a simple smart contract.

get to know solidity.

check out solidity by example section.

check out https://ethereum.org/en/developers/ for further resources.

check out https://gitter.im/ethereum/solidity/

familiarize yourself with OpenZepplin via youtube or OpenZepplin directly.

check out https://gitter.im/ethereum/solidity/

A SIMPLE SMART CONTRACT

Storage example:

```
pragma solidity >=0.4.16 <0.9.0;
contract SimpleStorage {
  uint storedData;
  
  function set(uint x) public {
    storedData = x;
  }
  
  function get() public view returns (uint) {
    return storedData;
  }
}
```
