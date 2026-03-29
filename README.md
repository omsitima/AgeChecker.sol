# AgeChecker.sol
How to deploy a contract on Base Chain AgeChecker.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AgeChecker {
    function isAdult(uint _age) public pure returns (bool) {
        return _age >= 18;
    }
}
