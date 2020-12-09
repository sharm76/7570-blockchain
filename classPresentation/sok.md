SoK

Introduction

Blockchain offers a platform through which mistrusting entities can cooperate in the absence of a trusting third party. Modifying a consensus mechanism implies changing one of the key element of a blockchain system while already in use, which creates crucial issues such as a lack of backward compatibility. The paper highlights layer two protocols are orthogonal scaling solutions. Contrary to the aformentioned solutions, layer-two protocols scale blockchains without changing the layer-one trust assumptions and they don&#39;t extend or replace the consensus mechanism. The place the consensus mechanism. The layer two protocol helps enable users to perform off-chain transactions through private and authenticated communication rather than broadcasting every single transaction on the blockchain.

In class Samuel identified myths that are scrutinized. They are as follows;

1. Blockchains cannot scale significantly — either in terms of throughput and computational complexity — without advances at _layer-one_, such as through novel or more efficient consensus mechanisms
2. Layer-two solutions can only be secure if the off- chain transaction volume is fully collateralized.
3. By default, off-chain transactions offer privacy
4. Blockchain transaction fees depend on their size or computational complexity, not on the transaction value.

The paper goes further to explain the layers of the blockchain. They divide it into four layers

1. Hardware layer:- Trusted Execution Environments (TEE) substitute the need for a blockchain clock with a trusted hardware assumption, thus enabling efficient protocols at other layers such as off-chain payments, the removal of dispute processes and backward compatibility.
2. peer-to-peer layer on which blockchain nodes exchange information asynchronously. Important for scalability, security and privacy of a blockchain. Blockchain miners are connected through dedicated miners P2P networks in addition to the public blockchain P2P networks.
3. The Blockchain layer – hosts immutable add-only chain of blocks that accumulates transactions from parties in a network. Integrity of the blockchain is ensured by means of a consensus algorithm, Proof of Work. Bitcoin-like blockchains are based on a restricted Script language and operate via a set of Unspent Transaction Outputs (UTXO)
4. The Off-chain Layer – assumes two properties, integrity and eventual synchronicity with an upper time bound. The layer does not publish every transaction on the blockchain immediately, and they heavily rely on the consensus algorithm of a parent chain. Two different protocols are discussed, Channels and Commit Chains.

One of the initial questions that was address in class was what was the difference between Side chain and the blockchain.?

The answer provided was that the Side chain is run parallel to the blockchain and are user defined, you can define new parameters
