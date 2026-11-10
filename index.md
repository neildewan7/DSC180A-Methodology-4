---
layout: default
---

# Neil Dewan
ndewan@ucsd.edu

Section: D35 -Blockchain
Mentor: Rajesh Gupta

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic we covered this quarter was learning what a blockchain is. 
Prior to this quarter I had only ever heard the term blockchain and had associated it with crypto-currencies such as Bitcoin. 
However after reading several white papers of big chains such as Bitcoin and Ethereum I learned that blockchains are just shared computers. 
I also learned about the different computers hosting the blockchain and how they get rewarded through mining, as well as how code can be run on a blockchain using smart contracts. 
I learned that a blockchain essentially can host 
public code, and since everything on a chain is public, these smart contracts can't be edited once 
put on chain. 

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

The investigation I would like to pursue for next quarter is to measure the true value of using a blockchain.
For our idea, we are planning on a system that issues student degrees on chain. The issue with this is that certain aspects of this
idea can potentially be used without a chain at all. For example, our degrees now are not issued on chain. However, there
are examples around the world of universities issuing degrees through a blockchain such as a chain of universities in Europe as well as IIT of India. The part I want to investigate
is how these provide value and whether or not we can reproduce that. One way of doing this is to implement a version of our idea without 
a chain and see the cost comparisons.


**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

Our approach for this quarter started from thinking of project ideas we could build off of past projects.
Instead of this approach I would have like to think more an application first. For example, who would use this tool,
what our goals, what are we trying to see. I think we got caught up in what a potential project idea is that we forgot
who and what we are building, as well as a stronger base on why we need blockchain for certain ideas.

**What other techniques would you be interested in using in your project?**

Some other techniques I would be interested in are diving deeper into different testnets and doing more in depth analysis on the differing costs. 
Another technique I have been thinking about is using Merkle trees to create a batching architecture. In the example of registering student grades, our current architecture supports 
each student's grade as its own on chain record. Instead of this, I would like to experiment with using Merkle trees so that 
each grade becomes a leaf node and that the leaves are then hashed together at the root. What this would allow is that a student would be able to prove their own
grade with a short proof without revealing others. This would lower our costs in total for every registration.
