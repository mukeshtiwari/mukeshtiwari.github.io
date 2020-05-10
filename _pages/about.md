---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello everyone, welcome to my personal website. My name is Mukesh Tiwari, and currently, I am a [postdoctoral researcher](https://findanexpert.unimelb.edu.au/profile/860472-mukesh-tiwari) at the [University of Melbourne](https://www.unimelb.edu.au) and working with [Toby Murray](https://findanexpert.unimelb.edu.au/profile/780796-toby-murray) on [verified information flow security](http://covern.org/). Before joining the University of Melbourne, I was a PhD student at the [Australian National University, Canberra](https://www.anu.edu.au/). During my PhD, I worked with [Dirk Pattinson](http://users.cecs.anu.edu.au/~dpattinson/) in formal verification of electronic voting. 

In my PhD, I addressed three main concerns posed by electronic voting, i.e. correctness, privacy, and verifiability. I addressed the correctness concern by using theorem prover to implement the vote counting algorithm, privacy concern by using homomorphic encryption, and verifiability concern by generating a independently checkable scrutiny sheet (certificate). You can read my [thesis](https://github.com/mukeshtiwari/Thesis/blob/master/thesisTemplate/thesis.pdf)(it's currently under review)(below is the abstract). 


Thesis Abstract
========
Since the introduction of secret ballots in Victoria, Australia in 1855, 
paper (ballots) are widely used around the world to record 
the preferences of eligible voters. Paper ballots provide three 
important ingredients: correctness, privacy, and verifiability. 
However, the paper ballot election brings various  other challenges, e.g. 
it is slow for large democracies like India,  and error prone for complex voting method 
like single transferable vote, and poses operational challenges for 
large countries like Australia. In order to solve these problems and various others, 
many countries are adopting electronic voting. However, 
electronic voting has a whole new set of problems. In most cases, the software 
programs used to conduct the election have numerous problems, including, but no limited to, 
counting bugs, ballot identification, etc. Moreover, 
these software programs are treated as commercial in confidence and 
are not allowed to be inspected by general member of general public. 
As a consequence, the result produced by these software programs 
can not be substantiated.

In this thesis, we address the three main concerns posed by electronic voting, i.e. 
correctness, privacy, and verifiability. We address the correctness concern by using 
theorem prover to implement the vote counting algorithm, 
privacy concern by using homomorphic encryption, and verifiability concern 
by generating a independently checkable scrutiny sheet (certificate). Our work 
has been carried out in Coq theorem prover.


