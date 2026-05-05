# PowerOfTwo.sol
PowerOfTwo.sol
pragma solidity ^0.8.20;
contract PowerOfTwo {
    function check(uint n) public pure returns(bool) {
        return n > 0 && (n & (n - 1)) == 0;
    }
}
