| No | Experiment List |
| -- | --------------- |
| 1. | [Cryptography in Blockchain, Merkle root tree hash](https://github.com/LifnaJos/HBCC601-Blockchain-Platforms/blob/main/PPT/Experiment_List.md#experiment--no-1) |
| 2. | Hands-on Solidity Programming Assignments for Creating Smart Contracts | 
| 3. | Implement the embedding wallet (Metamask) and transaction using Solidity |
| 4. | Implement a Private Ethereum  Blockchain using Geth |

# Experiment  No: 1
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
To find the Golden Nonce while solving the Cryptographic Puzzle
To construct a Merkle Tree for the given transactions
Prepare a document with Aim, Tasks performed, Program, Output and Conclusion.


