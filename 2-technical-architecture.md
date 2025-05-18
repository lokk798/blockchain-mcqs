# 2. Blockchain Technical Architecture and Basic Components

## Multiple-Choice Questions (MCQs)

1. **What is the primary purpose of a Merkle Tree in blockchain?**

   - To encrypt transaction data
   - To link blocks sequentially
   - To efficiently verify transaction integrity without downloading the entire blockchain
   - To generate public and private keys  
     **Correct Answer:** To efficiently verify transaction integrity without downloading the entire blockchain

2. **Which hash function is used in Bitcoin's Proof of Work (PoW)?**

   - Keccak-256
   - SHA-1
   - SHA-256
   - MD5  
     **Correct Answer:** SHA-256

3. **What role does the "nonce" play in a block header?**

   - It stores the Merkle Root
   - It is a random number used to achieve the difficulty target in mining
   - It encrypts transaction data
   - It acts as a wallet address  
     **Correct Answer:** It is a random number used to achieve the difficulty target in mining

4. **Which of the following is NOT a property of cryptographic hash functions?**

   - Deterministic
   - Reversible
   - Collision-resistant
   - Fast computation  
     **Correct Answer:** Reversible

5. **In a Merkle Tree, what does the root hash represent?**

   - The hash of the first transaction
   - The combined hash of all transactions in the block
   - The private key of the miner
   - The timestamp of the block  
     **Correct Answer:** The combined hash of all transactions in the block

6. **What prevents double-spending in blockchain?**

   - Public-key cryptography
   - Consensus mechanisms (e.g., PoW, PoS)
   - Light nodes
   - Block explorers  
     **Correct Answer:** Consensus mechanisms (e.g., PoW, PoS)

7. **Which component of blockchain architecture ensures fault tolerance if some nodes go offline?**

   - Merkle Trees
   - Peer-to-Peer (P2P) Network
   - Digital Signatures
   - Smart Contracts  
     **Correct Answer:** Peer-to-Peer (P2P) Network

8. **What is the purpose of a "light node" in blockchain?**

   - To store the entire blockchain ledger
   - To validate transactions without storing the full blockchain
   - To mine new blocks
   - To audit smart contracts  
     **Correct Answer:** To validate transactions without storing the full blockchain

9. **Which attack involves malicious actors gaining majority control of a network's mining power?**

   - Sybil Attack
   - Eclipse Attack
   - 51% Attack
   - DDoS Attack  
     **Correct Answer:** 51% Attack

10. **How does a digital signature ensure transaction authenticity?**
    - By encrypting the transaction with the recipient's public key
    - By hashing the transaction data
    - By signing the transaction with the sender's private key
    - By storing the transaction in a Merkle Tree  
      **Correct Answer:** By signing the transaction with the sender's private key

## True/False Questions

1. **A full node in blockchain stores only the most recent block headers.**

   - True
   - False  
     **Correct Answer:** False

2. **The Merkle Root in a block header is derived from the hashes of all transactions in the block.**

   - True
   - False  
     **Correct Answer:** True

3. **SHA-256 and Keccak-256 are examples of symmetric encryption algorithms.**

   - True
   - False  
     **Correct Answer:** False

4. **In Proof of Stake (PoS), miners compete to solve cryptographic puzzles to validate transactions.**

   - True
   - False  
     **Correct Answer:** False

5. **An Eclipse Attack isolates a node to manipulate its view of the blockchain.**
   - True
   - False  
     **Correct Answer:** True
