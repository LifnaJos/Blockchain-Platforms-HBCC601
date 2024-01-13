# List of Experiments for Extra Lab 

| No | Experiment List |
| -- | --------------- |
| 1. | [Cryptography in Blockchain, Merkle root tree hash](https://github.com/LifnaJos/HBCC601-Blockchain-Platforms/blob/main/PPT/Experiment_List.md#experiment--no-1) |
| 2. | [Hands-on Solidity Programming Assignments for Creating Smart Contracts](https://github.com/LifnaJos/HBCC601-Blockchain-Platforms/blob/main/PPT/Experiment_List.md#experiment--no-2) | 
| 3. | [Implement the embedding wallet (Metamask) and transaction using Solidity](https://github.com/LifnaJos/HBCC601-Blockchain-Platforms/blob/main/PPT/Experiment_List.md#experiment--no-3) |
| 4. | Implement a Private Ethereum  Blockchain using Geth |

## Experiment  No: 1
*AIM:* Cryptography in Blockchain, Merkle root Tree Hash

*Task to be performed :*

1. Make a copy of this [Google Colab Notebook](https://colab.research.google.com/drive/1RDlF1gtFp7Bxlkn0IQv01muSbfuTSajh?usp=sharing)
2. Try to solve the errors in each of the 4 Programs
3. In the 4th Program - Constructing a Merkle Tree Root Hash, modify the code as follows:
4. Update the transactions list with valid entries.
   
-- eg : transactions = ['A -> B : $10', 'B -> C : $5,'C -> A : $2']

- Sample Transactions to be considered 

-- T1 : Alice → Bob : $200; 

-- T2 : Bob → Dave : $500; 	

-- T3 : Dave → Eve : $100

-- T4 : Eve → Alice : $300; 	

-- T5 : Roo → Bob : $50

- Hash the transactions before combining them in the for-loop

-- Print all the intermediate hash during the construction of the Merkle Tree Root Hash

*Tools & Libraries used :* Python Libraries: hashlib

*Instructions :*
1. Cryptographic Hash functions in Blockchain
2. What is a Merkle Tree?
3. What is a Cryptographic Puzzle and explain the Golden Nonce
4. How does a Merkle Tree work?
5. Benefits of Merkle Tree
6. Use cases of Merkle Tree

*Outcome :*
1. Understood the concept of hashing, Cryptographic Puzzle to find nonce, Merkle Tree and its relevance.
2. Implemented programs
-- To find the Golden Nonce while solving the Cryptographic Puzzle
-- To construct a Merkle Tree for the given transactions
3. Prepare a document with Aim, Tasks performed, Program, Output and Conclusion.

## Experiment  No: 2

*AIM:* Hands on Solidity Programming Assignments for creating Smart Contracts

*Task to be performed :*
1. Go to [LearnETH Tutorials](https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null) provided by Remix IDE
2. Explore through Solidity Basics Course
3. Complete all the 19 Assignments provided with the Course

*Tools & Libraries used :* Remix IDE

*Instructions :*
1. Primitive Data Types, Variables, Functions - pure, view
2. Inputs and Outputs to Functions
3. Visibility, Modifiers and Constructors
4. Control Flow : if-else, loops
5. Data Structures : Arrays, Mappings, structs, enums
6. Data Locations
7. Transactions : Ether and wei, Gas and Gas Price, Sending Transactions

*Outcome :*
1. Understood the basics of Solidity Programming in writing Smart Contracts and Deploying them on the Remix VM.
2. Successfully performed the Assignments given in the Tutorial.
3. Prepare a document with Aim, Tasks performed, Program, Output and Conclusion.

## Experiment  No: 3

*AIM:* Implement the embedding wallet (Metamask) and transaction using Solidity 

*Task to be performed:* 			
- [Follow the GitHub repository for the experiment](https://github.com/LifnaJos/Embedding-Metamask-wallet-with-Remix-IDE-and-perform-transactions/tree/main#readme)
1. Set Up MetaMask:
-- Install MetaMask
-- Create or Import an Account:
-- Fund Your Wallet :  [Sepolia Testnet](https://github.com/LifnaJos/Getting-funds-from-Testnets-to-Metamask-Wallet/blob/main/readme.md#steps-to-get-funds-from-sepolia-testnet) (0.5 ETH per day) / RSK Testnet  (0.05 RBTC per day)
2. Connect the Sepolia Testnet  / RSK Testnet to Remix IDE       
3. Create a Simple Solidity Smart Contract based on the MiniPoject chosen
4. Compile and Deploy the Smart Contract.
5. Check the transaction details on the RSK Explorer
6. Interact with the smart contract 

*Instructions :*
1. What is a Metamask?
2. What is a test net?
3. List the steps to connect a Metamask with a Remix IDE for performing transactions.

*Outcome :*
1. Understood the steps for embedding the Metamask wallet with Remix IDE and perform transactions
2. Successfully performed the transactions on the Remix IDE via the account from Metamask Wallet
3. Prepare a document with the Aim, Tasks performed, Program, Output, and Conclusion

## 	Experiment  No : 4
*AIM:* Implement the Private Ethereum Blockchain using Geth

*Task to be performed :*
1. To install and set up an Ethereum network to create a private Ethereum blockchain for development and testing purposes. 
2. [Follow the instructions in this manual to set up a Private Ethereum Network](https://github.com/LifnaJos/private_ethereum_setup/blob/main/README.md)
-- Choosing a network ID
-- Choosing a consensus Algorithm
-- Creating a Genesis Block
-- Initializing the Geth Database
-- Setting up Networking
-- Running the member nodes
-- Running a Signer (In Clique)

*Note:* Download the [genesis file](https://drive.google.com/file/d/19Xwg1dKp2B3yhfNfSX81h0LDQRCTqWU6/view?usp=drive_link) and edit the account details (ie. Public Keys of the peers in the network)

*Instructions :*
1. What is Geth?
2. Significance of a Private Ethereum Network
3. Steps for creating a Private Ethereum Network

*Outcome :*
1. Understood the relevance of a Private Ethereum Network
2. Understood how to set up the Private Ethereum Network
3. Performed transactions between the nodes in the network
4. Checked the status of transactions in the Transaction pool
5. Prepare a document with Aim, Tasks performed, Program, Output and Conclusion.
