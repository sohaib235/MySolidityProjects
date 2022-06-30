# MySolidityProjects
// SPDX-License-Identifier: GPL-3.0
pragma solidity >=0.4.16 <0.9.0; 
contract MyCalculator  {   
function Addition(uint a, uint b) public pure returns(uint c) {
    c = a + b;
    return c;
}
function Subtract(uint a, uint b) public pure returns(uint c) {
    c = a - b;
    return c;
}
function Multiply(uint a, uint b) public pure returns(uint c) {
    c = a * b;
    return c;
}
function Divide(uint a, uint b) public pure returns(uint c) {
    c = a / b;
    return c;
}
function Power(uint a, uint b) public pure returns(uint c) {
    c = a**b;
    return c;
}
function Remainder(uint a, uint b) public pure returns(uint c) {
    c = a % b;
    return c;
}
}
