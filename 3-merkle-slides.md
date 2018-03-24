Goal: Summarize [this story](dear-mimi.md) in 3 slides to explain merkle (sans mining) in the context of the distributed web.

One of the things with the distributed web as envisioned by IPFS is that all content has a unique web address, that is independent of where the content is hosted.  So for example, currently, if you have all your cat pictures on Instagram, and Instagram shuts down, all the links you've shared to your cat pictures will no longer work. In this version of the web, your cat pictures will have a unique address that never changes. And if you change your cat picture, your changed cat picture will have its own unique address.  How does this work? 

There's something called a "merkle tree".  Or "merkle dag". Or "merkle".  Merkle was the last name of the man who invented this data structure. His first name was Robert. 

A Merkle tree is a data structure that locks data in place so that you can't change history.

A merkle tree is a data structure that, as I like to think of it, encodes history so that you cannot go back and change it. 
Merkle is the underlying data structure that allows cryptocurrencies like Bitcoin and Ethereum to function, so it's pretty important that people can't change what happened in Bitcoin because it would be changing who has how much bitcoin / money.

Let’s say we’re looking at some data on your computer and we want to store that data in a snapshot in time, let’s say we’re doing a backup.  
You have four things:  
* A picture of your cat
* a PDF of a book, 
* an mp3 of your favorite song, 
* and some data, an excel spreadsheet say. 
![Merkle with cats](CatMerkle.png "Merkle with Cats")
[TODO Walk through how the data is stored, explaining the merkle root]. You can easily check with the inputs if it matches the merkle root.

![Changed Merkle with cats](CatMerkleChanged.png "Merkle with a changed cat")
![Pig Latin v. SHA256](SHA256vPigLatin.png "Pig Latin versus SHA256")



