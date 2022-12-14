# GroupKey_SmartContract_Diffie-Hellman
A web tool used to establish Group Key Encryption via Diffie-Hellman by using a Smart Contract.

Requirements:
1. The necessary JavaScript script dependencies need to be added.
2. A web testing environment is required. (XAMPP is recommended for local testing)
3. MetaMask tool needs to be installed and configured.
4. The userManager.sol or old_userManager.sol smart contract needs to be transacted to a distributed blockchain and linked to the dApp. (Either private, main, or Ropsten *recommended*)

The main difference between userManager.sol and old_userManager.sol is that old_userManager.sol parses the string inside the smart contract whereas userManager.sol leaves that job to the client. Parsing strings inside a smart contract is operation intensive which translates to more gas which translates to inefficiency. 

I have authored a paper that was accepted to IEEE that describes the operation of this distributed application in closer detail. 

Paper Link: *[Private Group Communication in Blockchain via Diffie-Hellman Key Exchange](https://github.com/TheEliteOneShot/GroupKey_SmartContract_Diffie-Hellman/blob/master/Private%20Group%20Communication%20in%20Blockchain%20Based%20on%20Diffie-Hellman%20Key%20Exchange.pdf)*


