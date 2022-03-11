
Solidity function visibility specifiers:<br />
----------------------------------------------------------------------------------------------------------------------------
private: only visible in the current contract <br />
internal: can be called by the current contract or any derived contracts <br />
external: only visible externally, however can be accessed within the current contract via 'this.func' <br />
public: (default for functions) visible externally and internally (including getter functions for storage/state variables)<br />

Solidity function state mutability:<br />
----------------------------------------------------------------------------------------------------------------------------
view: Functions declared with view can read state but not modify it. <br />
pure: Functions declared with pure can neither read nor modify state. <br />
payable: Functions declared with payable can accept Ether sent to the contract. If 'payable' is not specified, the function will automatically reject all Ether sent to it.<br />

project content
----------------------------------------------------------------------------------------------------------------------------
in this smart contract sample  has "setName" and "getName" functions with solidity on blockchain
this example used ganache and truffle