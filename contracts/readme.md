----------------------------------------------------------------------------------------------------------------------------
Solidity function visibility specifiers:
----------------------------------------------------------------------------------------------------------------------------
private: only visible in the current contract 
internal: can be called by the current contract or any derived contracts 
external: only visible externally, however can be accessed within the current contract via 'this.func' 
public: (default for functions) visible externally and internally (including getter functions for storage/state variables)
----------------------------------------------------------------------------------------------------------------------------
Solidity function state mutability:
----------------------------------------------------------------------------------------------------------------------------
view: Functions declared with view can read state but not modify it. 
pure: Functions declared with pure can neither read nor modify state. 
payable: Functions declared with payable can accept Ether sent to the contract. If 'payable' is not specified, the function will automatically reject all Ether sent to it.