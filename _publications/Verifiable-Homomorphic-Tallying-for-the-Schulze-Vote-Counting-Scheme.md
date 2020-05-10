---
title: "Verifiable Homomorphic Tallying for the Schulze Vote Counting Scheme"
collection: publications
permalink: /publication/Verifiable-Homomorphic-Tallying-for-the-Schulze-Vote-Counting-Scheme
excerpt: 'The encryption of ballots is crucial to maintaining integrity and anonymity in electronic voting schemes. It enables, amongst other things, each voter to verify that their encrypted ballot has been recorded as cast, by checking their ballot against a bulletin board.'
date: 2019-07-13
venue: 'Conference on Verified Software: Theories, Tools, and Experiments - 2019'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-41600-3_4'

---

Abstract
-------
The encryption of ballots is crucial to maintaining integrity and anonymity in electronic voting schemes. It enables, amongst other things, each voter to verify that their encrypted ballot has been recorded as cast, by checking their ballot against a bulletin board.
We present a verifiable homomorphic tallying scheme for the Schulze method that allows verification of the correctness of the count—on the basis of encrypted ballots—that only reveals the final tally. We achieve verifiability by using zero knowledge proofs for ballot validity and honest decryption of the final tally. Our formalisation takes places inside the Coq theorem prover and is based on an axiomatisation of cryptogtaphic primitives, and our main result is the correctness of homomorphic tallying. We then instantiate these primitives using an external library and show the feasibility of our approach by means of case studies.

[Download Paper](https://link.springer.com/chapter/10.1007/978-3-030-41600-3_4)
[Coq code](https://github.com/mukeshtiwari/EncryptionSchulze/tree/master/code/Workingcode)
