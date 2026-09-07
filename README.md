// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract PonderPin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract FlipsidePin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SourcifyPin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract AderynPin {
    mapping(address => bool) public completed;

    function complete() external {
        completed[msg.sender] = true;
    }
}
