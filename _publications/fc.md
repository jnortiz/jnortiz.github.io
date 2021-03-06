---
title: "Faster Homomorphic Encryption over GPGPUs via hierarchical DGT "
collection: publications
abstract: 'Privacy guarantees are still insufficient for outsourced data processing in the cloud. While employing encryption is feasible for data at rest or in transit, it is not for computation without remarkable performance slowdown. Thus, handling data in plaintext during processing is still required, which creates vulnerabilities that can be exploited by malicious entities. Homomorphic encryption schemes enable computation over ciphertexts without knowing the related plaintexts or the decryption key. This work focuses on the challenge of developing an efficient implementation of the BFV scheme on CUDA. This is done by combining and adapting different literature approaches, as the double-CRT representation and the Discrete Galois Transform. Moreover, we propose and implement an improved formulation of the DGT inspired by classical algorithms, which computes the transform up to 2.6 times faster than the state-of-the-art. By using these approaches, we obtain up to 3.6 times faster homomorphic multiplication.'
date: 2021-03-04
venue: 'Financial Cryptography and Data Security'
url_slug: '2021-03-04-fc-spog'
paperurl: 'https://pdroalves.github.io/files/publications/2021-fc-spog.pdf'
bibtexurl: 'https://pdroalves.github.io/files/publications/2021-fc-spog.bib'
---