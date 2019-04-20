# Merkel-Tree

Suppose in a block the n transactions are Tx0, Tx1, · · ·, Tx(n-1) and the Merkle tree has already computed.

This program computes hash values needed to be put in the block so that when Txn is added, these hash values can be usedto compute the new root of the Merkle tree. So the input of the program is a positive integer n which is the number of transactions already in the tree and the output are hash values that should be in the block. 

For examples, if the input is 4, then the output should be: h(0..3), if the input is 5, then the output should be: h(0..3), h(4) where h(0..3) means h(0123), h(0..7) means h(01234567), etc.
