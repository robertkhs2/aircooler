**coolToken README**

**Introduction:**
The `coolToken` contract is an Ethereum smart contract written in Solidity. It implements a basic ERC20 token with additional functionalities such as minting, burning, transferring tokens, and redeeming air coolers using tokens.

**Features:**
1. **ERC20 Token:** The contract implements the ERC20 standard, allowing for the creation and transfer of tokens on the Ethereum blockchain.
2. **Minting:** The contract owner can mint new tokens and distribute them to specified addresses.
3. **Burning:** Token holders can burn their own tokens, reducing the total supply.
4. **Transferring Tokens:** Token holders can transfer tokens to other addresses.
5. **Redeeming Air Coolers:** Users can redeem air coolers using their tokens. Three types of air coolers are available: Portable, Room, and Window. Each cooler type has a specific cost in tokens and an available inventory.
6. **Owner Management:** Certain functions, such as minting tokens and adding air cooler inventory, are restricted to the contract owner.

**Usage:**
1. **Deploy the Contract:** Deploy the `coolToken` contract to the Ethereum blockchain.
2. **Mint Tokens:** The contract owner can mint new tokens using the `mintTokens` function.
3. **Transfer Tokens:** Token holders can transfer tokens to other addresses using the `transferTokens` function.
4. **Redeem Air Coolers:** Users can redeem air coolers by providing the cooler type and quantity of tokens using the `redeemAirCooler` function.
5. **Check Token Balance:** Users can check their token balance using the `getUserTokenBalance` function.
6. **Add Air Cooler Quantity:** The contract owner can add inventory for each type of air cooler using the `addAirCoolerQuantity` function.

**Security Considerations:**
- Ensure that only trusted entities have access to the contract owner's account, as they have significant control over the contract's functionalities.
- Implement proper access control mechanisms to prevent unauthorized access to sensitive functions.
- Use caution when interacting with smart contracts, especially when handling tokens and ether.

**Disclaimer:**
This contract is provided as-is, without any guarantees or warranties. Use it at your own risk, and exercise caution when interacting with smart contracts on the Ethereum blockchain.

**License:**
This code is licensed under the MIT License. See the `LICENSE` file for more details.

**Contact:**
For any inquiries or issues, please contact [contract owner's contact information].
