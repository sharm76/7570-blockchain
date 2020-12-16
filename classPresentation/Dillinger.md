# Security and privacy on Blockchain

# Introduction
This paper is a survey on security and privacy of Blockchain. It discuss the underlying the Blockchain technology in detail. Blockchain technology studied from two perspectives. From a data management view, it is a distributed database that records a list of transactions and organize them into a hierarchical chain of blocks. Meanwhile, from a security point of view, it is created and maintained by a peer to peer overlay network and secured using decentralized utilization of cryptography with crowd computing. In the past 5 years, several study were published on security and privacy of blockchain. In 2015, the first systematic exposition on Bitcoin and reviewed privacy enhancing method. Ghassan Karme overviewed the risks and attacks in Bitcoin like digital currency system. This survey provided in-depth empirical analysis of security attributes and advanced security properties of Blockchain. Besides, it discussed security solution to achieve security goals. 

# Contribution
The given paper is organized as follows:

- basic description on blockchain concept
- inherent security attributes in blockchain system
- consensus algorithms in blockchain-based system 
- the cutting edge security and privacy techniques
- overview the paper

# Blockchain

Blockchain is a secure ledger which organizes the growing list of transactions records into a hierarchically expanding chain of blocks, in which blocks are secured by cryptography methods to enforce integrity of transaction records. Blocks also maintain the hash value of the entire block itself, and the hash value of the preceding block in the blockchain, which leads to having a decentralized consensus procedure. This controls the consistency of data content of transaction records. 

The Bitcoin system takes advantage of Blockchain system decentralized consensus property and uses it as a distributed public ledger. This prevent the double spending for bitcoin transactions. Assume client A creates a bitcoin transaction to send bitcoins to client B. The created transaction should be validated by miners. To do this, the transaction is broadcasted to every node in the network. Then, miner nodes collect transactions into a block, verify them and broadcast the block to the network. Finally, the block is added to the blockchain, this bitcoin transfer from A to B will become finalized and legitimate. Hence, through the consensus process, each node has an option to add the new block to their copy of the global ledger or refuse it. The network ensures the consistency sate and prevents the double spending issue since it should be resilient to the attack.

Transaction technology in Bitcoin is based on UTXO this is the account based online transaction model which is extended in Ethereum. 

In the next part of the introduction, authors, introduced CAP properties in Blockchain as following: 
- Consistency: each computing node receives the most recent changes.
- Availability: any request to some data is always available. 
- Partition tolerance: the distributed system is always operational.

There are three main blockchains: Public, Private, and Consortium blockchain. 
Over the past 10 years, blockchain has evolved beyond digital currency, smart contract and many forms if decentralized collaborations with security and high level of trust. There are some requirements regarding security and privacy which are categorized as following: 

Consistency of a ledger, integrity of transactions, availability of system and data, prevention of double spending, confidentiality of transactions, anonymity of users, and unlinkability of transactions. However, there are some basic security properties that a blockchain must have, like strong consistency, tamper resistance, which means resistance to any type of intentional tampering to an entity by either the users or the adversaries with access to the entity, be it a system, a product, or other logical/physical object. Resistance to DDoS Attack is another basic property, which is distributed attack and it overload the host system by flooding with superfluous requests. Authors also pointed to other security properties, like Resistance to Double-Spending Attacks, Resistance to the Majority (%51) Consensus Attack, and Pseudonymity.

# CONSENSUS ALGORITHMS
The next section covers Consensus Algorithms, which is a group-based protocol for reaching agreement dynamically in a group. Compared to the majority voting, a consensus emphasizes that the entire group as a whole could benefit by reaching a consensus. Proof of work is one of the consensus protocol designed by Satoshi Nakamoto for Bitcoin. In nutshell, PoW algorithm rely on anti-centralization and economic incentives for security. It encourage users to solve the computational problems by giving rewards to them. The second introduced consensus algorithm is Proof of State, which represents an alternative type of distributed consensus protocols for ensuring the CAP properties of public blockchains. It breaks the dependency on rewards for security by promoting penalties-based solutions. BFT-based Consensus Algorithms are the next group of consensus algorithms, which is defined as the failure tolerance capability of a system against the BGP.

# privacy

The last section of the paper introduces some techniques to enhance the security and privacy of blockchain. First method is mixing, which was designed to prevent users' address from being linked. Next one is Anonymous Signatures, like group signature and ring signature. Homomorphic Encryption or HE is the third method. HE is a powerful cryptography which performs as certain types of computations directly on ciphertext. It makes sure that the operations performed on the encrypted data, when decrypting the computed results. The most recent solution is Game-based Smart Contracts. It encourages players to check computation tasks and find bugs. There are some other methods as Attribute-Based Encryption (ABE), Secure Multi-Party Computation, Non-Interactive Zero-Knowledge (NIZK) Proof, and The Trusted Execution Environment (TEE) Based Smart Contracts.

# Conclusion 
There are three remarks about security and privacy in a complex blockchain systems:

- item No single technology is a panacea for security and privacy of Blockchain.
- There is no technology that has no defects or is perfect in all aspects
- There is always a tradeoff between security, privacy, and efficiency

It is important to remember developing light-weight cryptographic algorithms as a security and privacy methods will be a key in enabling technology in the future development of blockchain.


