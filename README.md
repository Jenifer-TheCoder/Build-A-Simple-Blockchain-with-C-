# Build-A-Simple-Blockchain-with-C-
Build a simple Blockchain with C++  

Blockchain technology is skyrocketing with its new rivals on Cryptocurrencies and the way it is revolutionizing the business models. C++ being high efficient, speed providing language it is being used by many blockchain/smart contract application modules.

Blockchain with Proof Of Work
We implement a simple blockchain network with series of blocks using Proof of Work as an algorithm.

Proof Of Work
This method makes sure block in the network satisfies certain condition to be added into the node. The one who performs condition(cryptographic) operation will be named as "Miners/Nodes". THe entire process is called "Mining". Once the node gets added , the node/miner will get rewarded as cryptocurrency. The node can also maintain the network or provide support occordingly.

POW Algorithm used in this program:
  Here we have to create cryptographic hash that is acceptable by Blockchain network, network sets the difficulty level that can 1,2....N.Condition criteria is the number of zeros at the beginning of the SHA256 hash should be equal or greater than the difficulty level set by the network.If this condition is met , block will be added to the network, else hash will be re-created till it satisfies the condition. Kinda do-while loop by comparing the strings.

Build a Blockchain with C++
This implementation has three files to be added to the project. Steps are below:
- Create a new C++ Console Project named TestChainProj
- Create 2 new classes named Block, Blockchain(.cpp, .h)
- Create member variable & function signatures for both Block & Blockchain
- MineBlock plays an important role by creating SHA256 hash and comparing with char array of '0's with a size set to difficulty level.
- Here for simplicity the difficulty level is set 1
- Implement Block.cpp and Blockchain.cpp with all the requied functionalities like AddBlock, GetLastBlock, MineBlock with POW algorithm
- From the Main.cpp Add 3 blocks and wait the block data to be mined.

Hope it is useful to you, feel free to raise if there are any issues!
