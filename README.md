# My_Token
Overview:
MyToken is a basic ERC-20-like token smart contract written in Solidity. It supports minting and burning tokens, with public details on the token name, symbol, and total supply.

Features:
1. Token Details: name ("AlphaCoin"), symbol ("ALC"), supply (initially 1000).
2. Balance Mapping: balanceOf to track the balance of each address.
3. Mint Function: mint(address to, uint amount) increases total supply and the recipient's balance.
4. Burn Function: burn(address from, uint amount) decreases total supply and the sender's balance, ensuring sufficient balance.


Functions:
1. mint(address to, uint amount): Mints new tokens to the specified address.
2. burn(address from, uint amount): Burns tokens from the specified address.
