// SPDX-License-Identifier: MIT
pragma solidity 0.8.18;//this line defines the solidity version that i understand;

contract SimpleStorage {
    uint256 myNumber;//my number is automatically assigned zero;

    function store(uint256 number) public {
            myNumber=number;//this function looks like set function;
    }

    function retrieve() public view returns(uint256){
        return myNumber;//this function looks like get function;
    }
    
}
