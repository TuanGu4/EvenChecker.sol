# EvenChecker.sol
EvenChecker.sol9
pragma solidity ^0.8.20;

contract EvenChecker {
    function isEven(uint _num) public pure returns (bool) {
        return _num % 2 == 0;
    }
}
Update contract logic
Fix logic error
Add simple test case
Update state variable
Improve naming consistency
