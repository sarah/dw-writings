Goal: Summarize [this story](dear-mimi.md) in 3 slides to explain merkle (sans mining) in the context of the distributed web.

One of the things with the distributed web as envisioned by [IPFS](https://en.wikipedia.org/wiki/InterPlanetary_File_System) is that all content has a unique web address that is independent of where the content is hosted.  So for example, currently, if you have all your cat pictures on Instagram, and Instagram shuts down, all the links you've shared to your cat pictures will no longer work. In the IPFS version of the web, your cat pictures will have a unique address that never changes. And if you change your cat picture, your changed cat picture will have its own unique address.  

How does this work? 

There's a data structure, which is just a way of organizing data, called a "[Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree)".  Or "Merkle DAG" ([Directed Acyclic Graph](https://en.wikipedia.org/wiki/Directed_acyclic_graph)). Or "Merkle".  Merkle was the last name of the man who invented this data structure. His first name was Robert. 

A Merkle tree is a data structure that, as I like to think of it, encodes history so that you cannot go back and change it. It's the "no fake news" of data structures. 

Merkle trees are the underlying data structure that allow cryptocurrencies like Bitcoin and Ethereum to function, so it's pretty important that people can't change the record of what happened.

Merkle uses a lot of sophisticated math to cryptographically encode the data, but I’m going to explain it using [Pig Latin](https://en.wikipedia.org/wiki/Pig_Latin). 

Let’s say we’re looking at some data on your computer and we want to store that data in a snapshot in time, let’s say we’re doing a backup. As an aside, [git version control](https://en.wikipedia.org/wiki/Git) uses a similar structure to Merkle trees.  Anyway, you have four things:  

* A picture of your cat;
* a PDF of a book;
* an mp3 of your favorite song; 
* and some data, an excel spreadsheet say: 
![Merkle with cats](CatMerkle.png "Merkle with Cats")

The leaf nodes (nodes that don't have children) each encrypt a piece of data, in this case using Pig Latin. This means you have a leaf node for every piece of data you want to encrypt.  (On a blockchain, there's a leaf node for every transaction in a block, so the block itself has a Merkle root that validates all of its transactions.) 

Each parent node encrypts the value of its children, all the way up to the root of the tree. This means that the Merkle root has effectively "rolled up" every piece of data below it in the tree, such that any small change would change the root hash.

---
To illustrate this, let’s say you, or someone else, tries to tamper with your data, and they swap out the picture of your cat with a picture of a RED cat. Different cat.  Everything changes up this tree and your Merkle root is different. This is a sign that data has been changed and is no longer trustworthy:
![Changed Merkle with cats](CatMerkleChanged.png "Merkle with a changed cat")

---

Merkle trees use a cryptographic function called [SHA256](https://en.wikipedia.org/wiki/SHA-2) to encode the data, which is very complex and therefore safe for bitcoin and content-addressing.  If we built the new web -- or our cryptocurrencies -- on Pig Latin, our file names would grow ridiculously long, and it would be easy to hack.  

![Pig Latin v. SHA256](SHA256vPigLatin.png "Pig Latin versus SHA256")



