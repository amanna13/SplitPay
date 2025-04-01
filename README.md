# SplitPay Smart Contract
Splits payments among multiple addresses automatically using Smart Contracts.

## Overview 🌐
The `PaymentSplitter` smart contract is a Solidity-based contract designed to automatically distribute incoming Ether payments among multiple recipients. Each recipient gets a predefined percentage of the total funds, ensuring fairness and transparency in the distribution process. 🚀

### Key Features ✨
- **Customizable Distribution**: The contract supports different percentage splits among recipients, making it highly adaptable to various use cases.
- **Automatic Fund Distribution**: Once Ether is sent to the contract, it automatically calculates and sends the appropriate amounts to each recipient.
- **Simple and Efficient**: The contract is straightforward with no complex inputs or interactions. Just send Ether, and the contract handles the rest.
- **Secure and Transparent**: All transactions are executed on-chain, ensuring full transparency and security.

## How It Works 🔄

1. **Recipient Setup** 📑: The contract has a list of recipient addresses and predefined share percentages.
2. **Send Ether** 📤: Anyone can send Ether to the contract.
3. **Distribution Process** ⚙️: The contract calculates each recipient’s share based on the predefined percentages and sends the appropriate funds directly to their address.
4. **No External Input Needed**: Simply send Ether, and the contract handles the distribution automatically based on the predefined share structure.

## Example Scenario 📈
Let's say you want to split a payment among three recipients:
- **Recipient 1** will receive 40% of the payment
- **Recipient 2** will receive 30% of the payment
- **Recipient 3** will receive 30% of the payment

Once the payment is made to the contract, the funds are automatically divided and sent to each recipient’s wallet in the specified proportions. 🏦💰

## Usage 🔧

### Step 1: Deploy the Contract ⚙️
Deploy the contract on an Ethereum-compatible network (such as a testnet or mainnet). No input from the user is needed during deployment since the recipient addresses and their corresponding share percentages are predefined.

### Step 2: Send Ether 💵
Once the contract is deployed, anyone can send Ether to it. The contract will receive the funds and distribute them accordingly.

### Step 3: Automatic Distribution 📨
Once the Ether is received by the contract, the `distribute()` function will automatically calculate each recipient’s share and transfer the corresponding amount of Ether to each recipient.

## Contract Address 📍
The deployed contract can be found at the following Ethereum address:

**0x44379588862e8329BE182D66fEEe84b7844D3eBa** 🏷️

## Contract Design 💡
- **Recipient Addresses**: Predefined Ethereum addresses that will receive the funds.
- **Share Percentages**: Each recipient has a predefined percentage that determines how much they receive from the total Ether sent to the contract.
  
## Security 🔒
This contract uses basic `transfer()` calls to send Ether to recipients. Always ensure that recipient addresses are valid and that the contract is tested on a testnet before using it with real funds. 🧪

## License 📝
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing 🤝
We welcome contributions to improve the contract! Feel free to fork the repository and submit a pull request. Make sure to test your changes thoroughly before submitting.

## Contact 📬
For any questions or inquiries, open an issue in the repository, or feel free to reach out directly.

---

> **Note**: This contract is for educational and demonstrative purposes. Please thoroughly test and audit the contract before deploying it on the Ethereum mainnet. 💡

