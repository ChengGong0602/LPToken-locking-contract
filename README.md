# LP and Token Locking Smart Contracts
##  Token Locking smart contract
```
This is a smart contract written in the Solidity programming language for the Ethereum blockchain. It is intended to be used as a smart lock for tokens on the Ethereum blockchain, allowing users to lock tokens for a specific period of time before they can be withdrawn. The contract is using OpenZeppelin's Ownable, ReentrancyGuard, and SafeMath libraries, and is also importing an interface for an ERC20 token contract, called "IBEP20.sol". The contract has several structs, mappings, and events that handle the locking and withdrawing of tokens, as well as tracking statistics such as the total BNB fees and remaining BNB fees. The contract also has a constructor function that is called when the contract is deployed on the blockchain. The contract also has a function called "lockTokens" which allows users to lock a certain amount of tokens for a certain amount of time, and a function called "withdrawTokens" which allows users to withdraw their locked tokens after the lock period is over, and also deducts a BNB fee.
```

### Deployed Tokens Contract
- BEP-20 token on BSC testnet
https://testnet.bscscan.com/address/0x280192120d1967ce8ea4fcaa5924dc01a167983d#code 
Name: GoofyGoober   
Symbol:GG   
Total Supply: 100000   


### Deployed TokenLock Contracts
- SmartLock Contract on BSC testnet
https://testnet.bscscan.com/address/0xF807D8a9d5441b3D8329c56740966a5030Dcb0D7#code
