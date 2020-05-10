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

In my PhD, I addressed three main concerns posed by electronic voting, i.e. correctness, privacy, and verifiability. I addressed the correctness concern by using theorem prover to implement the vote counting algorithm, privacy concern by using homomorphic encryption, and verifiability concern by generating a independently checkable scrutiny sheet (certificate). You can read my [thesis](https://github.com/mukeshtiwari/Thesis/blob/master/thesisTemplate/thesis.pdf). Below is the abstract (it's currently under review). 


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

Expertise
========
My expertise lies in proving the correctness of any software implementation, i.e. theorem proving. I am fairly expert [Coq theorem prover](coq.inria.fr/), and recently, I started exploring [Lean theorem prover](https://leanprover.github.io/).  Other than these two theorem provers, I occasionally dabble with [Idris](https://www.idris-lang.org/) and [Isabelle](https://isabelle.in.tum.de/) (but nothing serious). 

Theorem Proving Journey
=========
In my undergrad, I was an avid problem solver which led me to explore various problem solving websites, e.g. [Online Judge](https://onlinejudge.org/), [SPOJ](https://www.spoj.com/), [Topcoder](https://community.topcoder.com/tc?module=ProblemArchive), and [Project Euler](https://projecteuler.net/). Among all these websites, only Project Euler allowed me to see the solution of other people once I solved the problem. My choice of language was C++ for solving problems, but looking at other people solution, the one language that really impressed me was [Haskell](https://www.haskell.org/). It was my first encounter to a functional language, and I still remember my first Haskell implementation of [Baby-step giant-step algorithm](https://mukeshiiitm.wordpress.com/2011/02/14/baby-step-giant-step-algorithm/), [Tonelli–Shanks algorithm](https://mukeshiiitm.wordpress.com/2011/02/13/shank-tonelli-algorithm/), and [Project Euler 94](https://mukeshiiitm.wordpress.com/2011/02/11/project-euler-problem-94/). During Haskell exploration, one thing I would frequently encounter is equational reasoning and dependent types. To explore these topics, someone at haskell irc suggested me to try Coq. I am using Coq since [2014](https://mukeshiiitm.wordpress.com/2014/08/22/proving-theorems-in-coq/), and since then, I never looked back. It was one of the best decisions of my life. 
