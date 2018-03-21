## Dear Mimi,

I can picture talking to you in our Indian restaurant and you letting me slog through a long explanation for something, asking clarifying questions and enjoying metaphorical romps, failed and otherwise. I've recently decided to learn this thing called blockchain, which is challenging and complex and so I've invented you as my imaginary dinner guest while I try to explain it, to you, but really to myself.  Having an imaginary conversation with you helps me see if I understand it enough in non-technical parlance to get the fundamental ideas across.  But I've since cleaned up the letter a bit, taking out identifying names and too many personal segues. Maybe others will get something out of it, too. 

You be the judge! 

The first I'd consciously heard of Blockchain, it entered my consciousness sort of sideways, as most things do. A friend had left their high-paying job to go learn about it for a while.  I could tell you two words about blockchain at the time: it has to do with bitcoin, and also The Future. ("bitcoin" and "future" were my two words). Anyway, I remember feeling kind of jealous. That type of pang that tells you: this is something I want to do.  I want to go back to the beginning, or the beginning of something new, and figure it out. It just grabbed my imagination. 

So, what is the blockchain. The Blockchain.  I'm gonna start this way, for context. You've probably heard of bitcoin.  And probably don't know much if anything about it except it exists. And is...

### Some kind of weird digital money.  

And it is.  [Bitcoin](https://bitcoin.org/en/) is where we'll start.  So basically, in 2009, after the whole economy collapsed, an anonymous person or personS going under a pseudonym [wrote a paper & published it to the internet](https://bitcoin.org/bitcoin.pdf) & the gist was: I've figured out how to make digital money that is no longer controlled by a small group of self-interested people, this is how, and by the way, I've done it. 

People have been trying to make digital money for a long time, in various iterations, and main reason it is hard to make digital money is because of copying. Essentially, how do you avoid copy-pasting money the same way you copy-paste your bootlegged music files.  

Let's punt for a minute on what digital money IS, but in order to get a loose mental model going, imagine that you have--similar to having a file on your computer--a dollar on your computer. And you can give me that file/dollar, and I can use that file/dollar to buy a soda. Except it's not called a "dollar", it's called a "whatever" (a "bitcoin", or an "ether", etc), and I can use it to buy a soda, and the soda is a soda.  

Now, if you have a paper dollar in your hand, and you give it to me, it's physically clear that there was one paper dollar, and now it's in my hand, and not in your hand. 

And if you have a _record of a paper dollar_ in your online Chase Bank account, and you send it to _my_ online Chase Bank account, Chase itself has detailed records of that happening. Chase knows that you had a dollar, you gave me a dollar, now you have one dollar less than you had before; and now I have one dollar more than I had before.  

That's four things it knows. 

And in fact, if anywhere between "you had a dollar" and "now I have a dollar more than I had before" any one of those other steps failed, Chase would undo all four steps, getting back to the simple fact of the matter than you have a dollar.  Because unless all of those things happen nothing happens. All or nothing. This is called a "transaction".  It consists of a list of steps that are dependent on each other to complete a larger step. If any of the steps failed, they all "roll back". Undo. Go back to where they were at the beginning. 

Without this transaction, if something goes wrong, you are short a dollar (maybe), I don't gain a dollar (or maybe I do), where did that dollar go, it's all chaos. 

So there are these two situations we historically have for money exchange. One, you and I standing next to each other at the pizza place, handing a dollar back and forth. The other, you and I trusting someone else. And pretty much to date, that someone else we trust has a big logo, lots of TV ads, lots of mindshare, lots of physical presence... Chase Bank.  Of course we're going to trust the bank.  It's what we do. It's what we've always done. 

So [Satoshi Nakamoto](https://en.wikipedia.org/wiki/Satoshi_Nakamoto) come along with a third way that says: What if you could give me a dollar, online and through your computer, and I could get that dollar, and I could buy a soda with it, but, we didn't need Chase, we didn't need to know each other at all, and there is no way that you could copy that dollar, and give it to a bunch of people, doubling, trebling or gazillioning your profits.  

That's the premise. 

In a world like that, Chase could go away.

### What is a dollar, anyway? 

To be very simplistic about it, it's a thing that you and I agree has a certain amount of "value". And that everyone we know, Republicans and Democrats, poor people and rich people, U.S. citizens and non-, agrees, has a certain amount of "value".  We all of us agree it is the same, so if you tell me, "This hamburger costs me 16 dollars" we can all understand that "that's an expensive burger". 

Interestingly, this is one reality we don't dispute. 

There are other considerations. The dollar used to be pegged to gold, which meant it had an actual, redeemable, gold-rock value. This is no longer the case. How many of them are "in circulation".  What can you get for "todays dollar" compared to "yesterdays dollar".  How many of these things called "a dollar" do you need to get things called "a peso" that other people in far away lands use to buy _their_ sodas.  How many of these things called "a dollar" will someone give you to get your house, to go to work, etc.  Things that are scarce cost more dollars, like land in Park Slope; things that are common cost less dollars, like a coke, though over time everything costs more dollars, just talk to an old person about what they could get for a nickel, 1/20th of a dollar, Way Back When. 

But it's basically an agreement,  a shared reality. And given that it is no longer backed by exactly some amount of gold bars in a safe somewhere, it's more of a shared agreement than an actual proxy. I mean, I could change my dollars for some gold coins; and so could you; but if we all decided to do it at the same time (ref [It's A Wonderful Life](https://en.wikipedia.org/wiki/It%27s_a_Wonderful_Life)), it won't work. There's not enough. The world falls apart and we realize that this agreement-thing is Not True After All and all hell breaks loose. 

So it's basically an agreement that is tracked by careful observation. In small cases, "I" observe "me" giving "money" to "you". In larger cases, an authoritative entity like a bank keeps track of who owns how much, how much was spent, where it went, etc.  We all trust that entity to keep track.  Or entities, because of course it's never as simple as you in Bank One give me money in Bank One: it's more like your "Bank One" pays your "Bank Two" money and then you move money from "Bank One" to "Store Seven" to buy a dress.. and nowadays that all happens, or it _can_ happen, without human beings at all, but online through transfers and lots of electronic communications behind the scenes to make sure everything is kept track of ends up in the right place, and we of course, get the soda, or the dress. 

That entity, or entities, is between all of us. Citibank, Chase, U.S. Bank, Bank Whatever... some small set of authorities that we all trust to keep track of how much of this "money" thing we each have, and where it goes. 

So Nakamoto comes along.  And they say, money is an agreement, we don't need the middleman to share it, and, furthermore, we don't need our identities tied up with it. In short, here's a way for you to give me money without "you" knowing "me", but everyone agreeing that the money you gave me is real and thus, in some world, I can use it to buy my soda. 

And while we're at it, let's not call it a "dollar". In this case let's call it a "bitcoin", but really, go to town, you can make  your own money and call it whatever you want, a "mimi", if you will, and it will work the same. 

I'm going to try to explain the system that lets this work. 

### It's a chain of agreements. 

To keep track of the transactions, or the "money" being spent, a chain of agreements is built.  What does this mean. 

Every agreement relies on the one came before it. 

Which relies on the one that came before _it_.

Which relies on the one that came before _it_.

Etc. etc. until we're in the Garden of Eden, the beginning, and (technically speaking) what is actually called [The Genesis Block](https://en.bitcoin.it/wiki/Genesis_block). 

Or rather than agreements, say, it's a chain of facts. 

Where each fact relies on the fact that came before it. 

Which relies on the one that came before _it_. 

Which relies on the one that came before _it_....

Etc. etc. and now, again!, we're in the Garden of Eden. 

Over time, a chain of facts has been built such that if one fact changes, the entire chain breaks.  Think for a moment of a knitted scarf: you can't simply extract one stitch without impacting the ones it is built on. 

### Getting facts in the chain

Now let's switch metaphors for a moment and imagine that this chain of facts is not transmitted directly from you to me, but from you to me by way of a chorus. This is not exactly how the chorus was used in [Greek theater](https://en.wikipedia.org/wiki/Greek_chorus), but I'm going to put out that image of the chorus and see how far it can take us. 

So imagine that there's a giant chorus continually singing these facts, facts that go back all the way back to the end of time, so if any false fact gets introduced the song gets messed up and the false fact gets evicted.

### Can Pig Latin help us? 

In an actual blockchain, there's a whole part about how facts get in the chain (song) that has to do with codes and [complex math around codes](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography), and I'm going to try to get the gist of that across without going into technical specifics related to the blockchain itself. 

So, when I was little I was interested in [pig latin](https://en.wikipedia.org/wiki/Pig_Latin). With secret codes in general. Were you? Was it a girl thing? I feel like it was ostensibly a "boy thing" with decoder rings and War (somehow) but there's a part of me that feels like little girls were quietly making secret codes all the time.  Pig Latin is a silly, easily "decodable" code, but it's a specific protocol for encoding language and it's one we know from the playground. And in fact, Pig Latin was used, I'm sure more than once, to transmit let's say, chains of gossip on a schoolyard.  So, our tools for understanding how you can't change facts in our chain are:
* Pig Latin; 
* Unchangeable history; 
* A chorus, keeping it so.
* The idea of gossip -- or, how does gossip become fact

### The chain of history
In the blockchain, for a fact to get added to the chain (or knitted scarf) of history, it has to also, somehow, represent the thing that came before it as well as its own truth. Let's try with some memories from my youth. We're going to take a memory and "encode" it: 

```
First Fact: Schoolyard lunch.
Pig Latin Fact: OolyardSchay UnchLay
```
We have a fact, we've encoded it.

```
Fact 1: Quentin Ertel kissed Sarah Carlson. 
Pig Latin Fact: EntinQuay RtelEay IssedKay ArahSay ArlsonCay. 
Special Fact Code: EntinQuay RtelEay IssedKay ArahSay ArlsonCay OolyardSchay UnchLay
```
But wait!  Notice that there are two "facts" there. One is simply the encoded version of _Fact 1_ and the other is _the encoded version of Fact 1 PLUS the encoded version of our first fact_.

```
Fact 2: Nicky likes Kerry
Pig Latin Fact: IckyNay IkesLay ErryKay
Last Fact: EntinQuay RtelEay IssedKay ArahSay ArlsonCay. 
Special Fact Code:  IckyNay IkesLay ErryKay _EntinQuay RtelEay IssedKay ArahSay ArlsonCay OolyardSchay UnchLay 
```
Similar, but now we have another fact. We have our fact, our encoded fact, our previous fact, and our "special fact code" that combines all of them into one. 
```
Fact 3: Megan likes Nicky
Pig Latin Fact: EganMay IkesLay IckyNay
Last Fact: IckyNay IkesLay ErryKay
Special Fact Code: EganMay IkesLay IckyNay _IckyNay IkesLay ErryKay EntinQuay RtelEay IssedKay ArahSay ArlsonCay OolyardSchay UnchLay
```
This is a chain of facts. And each important piece of gossip is encoded in the (very unsafe & unsecure) code we call Pig Latin.  And every piece of gossip has a "Special Fact Code" that as you can see references ALL THE FACTS THAT CAME BEFORE IT.  All the way back to the garden of eden, the P.S. 321 lunchyard. 

Quick aside: in my example above, the "Special Fact Code" gets longer & longer with each new fact. But in computer-land, because of Math & Science, that "Special Fact Code" stays the same amount of digits, even while it encodes all the same information.

Now, imagine that every child in the schoolyard has this whole list in their heads, from First Fact through Fact 3 and beyond... as far is it goes. They all have (because imagine for a moment that they are clones and not children) the exact, letter-perfect, same set of facts in their head. 

You can't take Fact 2 out of the sequence, because if the sequence, as is,  went from Fact 1 to Fact 3, the "Special Fact Code" on "Fact 3" wouldn't make any sense. It would contain a reference to information that didn't exist. It would contain a "Last Fact" that wasn't, in fact, the last fact, and in the "Special Fact Code" it would have information that didn't exist before it.  There would be this demonstrable break in the chain of facts that couldn't be accounted for. Even if we changed the name "Fact 3" to "Fact 2", when you look at all the information that comes along with it, as you can see belong, something is wrong. _IckyNay IkesLay ErryKay_ isn't accounted for anywhere. 

```
First Fact: Schoolyard, lunch.
Pig Latin Fact: OolyardSchay UnchLay
```
Good, as before
```
Fact 1: Quentin Ertel kissed Sarah Carlson. 
Pig Latin Fact: EntinQuay RtelEay IssedKay ArahSay ArlsonCay. 
Special Fact Code: EntinQuay RtelEay IssedKay ArahSay ArlsonCay OolyardSchay UnchLay
```
Same, as before
```
Fact 2: Megan likes Nicky
Pig Latin Fact: EganMay IkesLay IckyNay
Last Fact: IckyNay IkesLay ErryKay
Special Fact Code: EganMay IkesLay IckyNay IckyNay IkesLay ErryKay EntinQuay RtelEay IssedKay ArahSay ArlsonCay OolyardSchay UnchLay
```
Wait -- that "Special Fact Code" is wrong because it references something that is not in our chain of facts.

### Let's go back to our cloned children for a moment. 

We have a schoolyard of children who all have the exact same set of facts in their heads. Let's say there's 100 of them. And if you asked them what happened at Schoolyard that lunchtime, they could all rattle through to the last fact, and give its code,  "EganMay IkesLay IckyNay IckyNay IkesLay ErryKay EntinQuay RtelEay IssedKay ArahSay ArlsonCay OolyardSchay UnchLay"

Now, imagine a new child wanders onto the courtyard.  And she's singing a different set of facts. Maybe it's close, it probably is, but it's off in one or two places. It leaves out some critical information. What happens? Well, simple. It's one child singing. There are 100 others. The 100 others win. The 1 child gets killed, her song forgotten, and the new song replaced in her head. Maybe she's not killed, but 100-1, her song gets replaced, and now there are 101 children singing the same song. If you doubt this is what happens, you've not spent much time on a Brooklyn playground.

Next case, say 102 children come to the schoolyard where the 101 children are congregated, (this is very Sharks & the Jets) and the 102 children have a different version of the song, their song wins. Do the math. You have 203 children, 51% of them believe Thing A, 49% of them believe Thing B, they're children, it's very Lord Of The Flies, by the end of lunch there are 203 children singing Thing A.   

We'll come back to this. The "children" don't really win in a clobber-brute-force kind of schoolyard fight, but just hang onto it for a moment.  The point is, the majority of children, their song wins.  

Of course, you know and I know this isn't how schoolchildren learn, or gossip, or repeat things. they don't all stop and sing, they don't clobber each other in literal competing armies based on size, they don't repeat long strings of pig latin in order to keep track of history. But ...

### Facts spread from power centers. 
Even if facts are not "facts", they become indistinguishable from them as they spread from power centers.  

Power centers in high school: David, Paul and John said Sarah P. came into the Green Room, stripped, and begged them all to have sex with her.  This wasn't true, but those three came out and said it and from then on 1000 high school students repeated it like gospel. The facts came from the power centers and they held. 

Power centers in elementary school: Sarah, Dorian, Joanna, Leila. Did or didn't something happen and was it important? That's where you took your cues. If a non-power-center student, say Jenny B., had a challenge, it wouldn't be heard, but when Joanna Abbott walked up and down our 5th grade lines on St Patrick's day tapping everyone in turn and telling them "you're lame" if you weren't wearing green, it was a fact. (I think I was wearing all green, tights shoes skirt shirt eyes. which was equally lame for being over-prepared.)

Power centers are controlling facts everywhere.  I added those two examples because it's interesting to think about the effect of power-centers in "Fact chains" outside of technology. Perhaps some of those anecdotes can point us towards ways in which our technological systems can, have and will be abused. 

### A new event

So you have your list of facts. Each fact references the fact before it, so if the fact before it changes or goes missing, the entire list from there on out is wrong. And you have a chorus, the majority of which agrees on the current set of facts, and the chorus has mechanisms to keep false fact out.  Time progresses, the chain gets longer, it is harder and harder to change. 

Something new happens.  Let's say, for the sake of my 5th grade fantasy, that Jed Tells Phoebe He Likes Me.
```
New Fact: Jed Tells Phoebe He Likes Me.
Pig Latin Fact: EdJay EllsTay OebePhay eHay IkesLay EMay. 
```
How does that get in the song? 

### How can we make that... true? 

Well, we need to get it through a power center, that has the power to **Make It So**. So we effectively put it to market: who is going to pick it up and add it to the song? 

First of all, what is even the motivation to do so? Let's presume there even is a set of power centers that have the ability to notarize, effectively, and push information into the song. Why would they do it? What's in it for them? Ok, first off, let's say, more power. If you are Dorian E and you continually have new information, you get more respect and popularity than you already had. If you're Jenny B, well, you may as well try -- you have nothing to lose!

And so it's economic. There's an incentive to do the work to get the new verse added because, in the case of the kids, it will reflect well on them. 

But for bitcoin and blockchain we don't have children. We have computers, set up by humans, that are running code, and we call these computers "miners". Miners get actual money for the time & energy they invest.  But either way--a child looking for status, or a computer run by a money-hungry individual--you get paid in the currency that matters. 

And your job is to validate the new fact and add it to the song (or chain; or knitted scarf) first. Then you get the benefits of being the messenger.  You have to do a bunch of work to get it done: you have to calculate the last fact & the special fact code before anyone else does, and then you need to re-transit the song, with its new verse, to the children.

In computer-land it's not Pig-Latin, so those computations [take a tremendous amount](https://www.google.com/search?q=bitcoin+mining+farms&tbm=isch&tbo=u&source=univ&sa=X&ved=0ahUKEwiGkv3Jh_7ZAhXmqFkKHVz6B2YQsAQIMQ&biw=1920&bih=934) of [time](https://www.quora.com/How-much-CPU-time-is-needed-to-mine-1-bitcoin) and [energy](https://powercompare.co.uk/bitcoin/). What the computations DO have in common with Pig Latin, though, is that it very easy to tell from the output that the input was correct.

### Rough Summary
Event -> Submitted to Miners -> Mining computation solved -> Solution verified by other miners --> Event added to the Chain

By having a verifiable chain of facts, kept "honest" by lots of distributed miners that need majority consensus to encode a new fact in the chain, you get a "chain of history" that cannot be tampered with unless you are also able to tamper with the underlying power centers and get 51% of the power.

This effectively stops the problem of you attempting to cheat by sending sending the same "dollar/file/bitcoin" to two people at the same time. This is because the history cannot correctly encode both transactions into the chain: you would need a group of more people speaking louder (or 51% of all the computers in the world who are mining bitcoin) to override the historical set of facts needed to be verified by the chain.  

And that's the blockchain: a series of transactions knitted together over time and verified by a distributed network of individuals. These transactions can send "money", they can keep track of events, they can sell [crypto-kitties](https://www.coindesk.com/a16z-leads-12-million-funding-for-ethereum-app-cryptokitties/) on the Internet. In short, a blockchain can be used for many purposes.  

What we didn't talk about is how you can send and get your money on the bitcoin blockchain, but if you think of sending money like an "event", then any time you send or receive money, you initiate an event that goes through the process described above, so that it is verified as fact.  There's more to sending money (in this case bitcoin) but suffice it to say, you have an account, the account has an address, and to send bitcoin you create an event that transfers money from your address to a new one; and to receive bitcoin you give someone your address and they send you money.  Your address has a public component that you can share, and a private component that only you know, and that is used to verify your identity.  This post focuses more on the chain of truth in verifying transactions instead of the mechanics of what the events are and how they work on a granular level, but that's enough to wave some hands at.

### There are lots of blockchains
Not just one. I imagine in a few years a blockchain will simply be a commodity technology like a database, something you use but don't think about. But for now, they're in a period of growth explosion. You have the blockchain powering Bitcoin, a different blockchain powering Ethereum (a different kind of digital money); other digital currencies but that _use_ the Ethereum blockchain; other digital currencies that are inventing their own blockchains, and new, experimental, commercial and non-commerical solutions.  Some of the blockchains offer new functionality, in addition to the ability to send bitcoin or other transactions around. 

They are looking at how to solve the consensus problem not through mining power that uses electricity only but through other methods like proving you have a certain ["stake"](https://en.wikipedia.org/wiki/Proof-of-stake) in the chain or a certain ["authority"])https://en.wikipedia.org/wiki/Proof-of-authority) to verify transactions. There are chains, no longer even called "chains" but "tangles" where miners [create & verify transactions at the same time](https://iota.org/).  In short, this is an exploding area of research and experimentation, with the goal of decentralizing financial transactions and making tamper-proof record-keeping while not destroying the environment in the process.

But that is for another day.

The main thing I wanted to talk about today, how a chain of trust gets created, let me know if that makes sense, where there are gaps, and what your questions are!

I'll get the check! xo, 

Sarah



