# Information-Theory
This repository contains examples of code that illustrate basic concepts in Information Theory.

Our course follows in the footsteps of Claude Shannon's groundbreaking paper, "A Mathematical Theory of Communication".
In this paper, Shannon considers the general problem of transmitting information over a communication channel.

The first interesting question that we ask is: What is the most efficient way to send a message over a noiseless communication channel? That is, we want to encode our information in as few bits as possible before sending it. In other words, what is the best way to compress information?

The answer can be exressed in terms of a mathematical function called entropy, which relies on the assumption that the information is drawn at random from a distribution over the set of all possible messages. Thus, the effiency of the encoding relies crucially on our ability to effectively model the message space as a random process with minimal entropy.

The second question that we ask is: How can we accurately transmit a message over a noisy communication channel?
For simplicity, we consider these two questions completely seperately, although they are of course connected.
It is possible to combat noise by adding some redundancy to the message. It is easy to see how this could reduce the error probability while increasing the message length. 

Shannon's surprising discovery was that by encoding blocks of bits together, it is possible to attain essentially zero error probability without increading the message length too much. The best result of this form that is acheivable can also be described in terms of the entropy function.

The purpose of this repository is to provide supplementary material for the course. During the semester, I will post bits of code that demonstrate some of the algorithms and principles discussed in class.
