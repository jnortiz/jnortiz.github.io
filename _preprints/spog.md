---
title: "Faster Homomorphic Encryption over GPGPUs via hierarchical DGT"
collection: preprints
abstract: 'Privacy guarantees are still insufficient for outsourced data processing in the cloud. While employing encryption is feasible for data at rest or in transit, it is not for computation without remarkable performance slowdown. Thus, handling data in plaintext during processing is still required, which creates vulnerabilities that can be exploited by malicious entities. Homomorphic encryption (HE) schemes are natural candidates for computation in the cloud since they enable processing of ciphertexts without any knowledge about the related plaintexts or the decryption key. This work focuses on the challenge of developing an efficient implementation of the BFV HE scheme on CUDA. This is done by combining and adapting different approaches from the literature, namely the double-CRT representation and the Discrete Galois Transform. Moreover, we propose and implement an improved formulation of the DGT inspired by classical algorithms, which computes the transform up to 2.6 times faster than the state-of-the-art. By using these approaches, we obtain up to 3.6 times faster homomorphic multiplication.'
date: 2020-07-09
venue: 'Cryptology ePrint Archive'
url_slug: '2020-eprint-fasterhe'
paperurl: 'https://eprint.iacr.org/2020/861'
bibtexurl: 'https://eprint.iacr.org/eprint-bin/cite.pl?entry=2020/861'
---