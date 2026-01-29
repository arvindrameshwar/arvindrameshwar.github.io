---
layout: page
title: ECC-2026
permalink: /2026-Jan-ECC
---

## EE5160: Error-Control Coding (Jan.--May 2026)

**Instructor**: [Arvind Rameshwar](arvindrameshwar.github.io)

**Time and Location**: Wednesdays (15:30--16:45 hours), Fridays (14:00--15:15 hours)
                       at ESB-242. The first class is on Wednesday, 21 January 2026.
                       
**Office Hours**: Thursdays (15:00--16:00 hours); do send me an email in advance

### Course Description

The objective of error-control coding (or coding theory) is, at a high level, to maximize the amount of information transmitted/stored across/in a noisy, erroneous medium, while ensuring reliable recovery of the information. The theory of error-correcting codes goes back to Shannon (1948) and Hamming (1950), and has been a cornerstone in the evolution of modern communication technologies and the internet. With the growth of research and development in quantum computing, error-correcting codes will play an increasingly important role in ensuring the fidelity of data against noise, both classical and quantum. In addition, coding theory has applications beyond data computation and storage, in fields ranging from cryptography to synthetic biology to computational epidemiology.

In this course, we shall build the foundational tools for designing "good" error-correcting codes. The course can be partitioned into four unequal parts:

1. **Foundations**: What makes a code "good"?
2. **Fundamental limits**: How "good" can a code get?
3. **Classical constructions**: How does one use the rich mathematical theory of linear algebra to design "good" codes?
4. **Modern constructions**: What are "good" codes for "information-theoretic" channels?

### Prerequisites

Comfort with basic linear algebra and probability, in addition to familiarity with understanding and writing mathematical proofs.

### Tentative List of Topics

Block codes, linear codes via an introduction to vector spaces, bounds on code parameters, Shannon's noisy coding theorem, operations on codes, finite field arithmetic, Reed-Solomon codes, BCH codes, Reed-Muller codes, list decoding, LDPC codes and factor-graph interpretations, a brief overview of density evolution for the erasure channel

### Grading

There will be three examinations: two midterms and a final, and a collection of take-home assignments. The exams will closely follow the course material, and the take-home assignments are meant to supplement and extend the lectures.

* Midterms: 40% (20% each)
* Final: 30%
* Assignments: 20%
* Class participation: 10%

### Schedule

Handwritten lecture notes will be made available at the end of every module.

1. [Introduction and course overview]({{ site.baseurl }}/2026-Jan-ECC/Ecc-2026-l1.pdf) (21/1)
2. [Preliminary definitions, MAP decoder, minimum distance decoder]({{ site.baseurl }}/2026-Jan-ECC/Ecc-2026-l2.pdf) (23/1)
3. [Shannon's noisy channel coding theorem]({{ site.baseurl }}/2026-Jan-ECC/Ecc-2026-l3-Shannon.pdf) (28/1)

### Selected Useful Online Courses and References

#### Courses

1. Prof. Venkatesan Guruswami's courses at CMU: [15-859Y: Coding Theory, Fall 2014](https://www.cs.cmu.edu/~venkatg/teaching/codingtheory-au14/) and [15-859V: Introduction to Coding Theory, Spring 2010](https://www.cs.cmu.edu/~venkatg/teaching/codingtheory/)
2. Prof. Henry Pfister's course at Duke University: [ECE 590.10: Error Correcting Codes](http://pfister.ee.duke.edu/courses/ece590_ecc/)
3. Prof. Alexander Barg's course at the University of Maryland: [ENEE 626: Error Correcting Codes](https://www.terpconnect.umd.edu/~abarg/626/)
4. Prof. Prahlad Harsha's course at TIFR, Mumbai: [CSS.318.1: Coding Theory - Monsoon Semester (2022-23)](https://www.tcs.tifr.res.in/~prahladh/teaching/2022-23/coding/#ref)
5. NPTEL courses by [Prof. P. Vijay Kumar](https://www.youtube.com/playlist?list=PL85783E9E7B5F2C0D) and by [Prof. Andrew Thangaraj](https://nptel.ac.in/courses/117106031)
6. Lecture notes by Prof. G. David Forney at MIT: [6.451: Principles of Digital Communication II](https://ocw.mit.edu/courses/6-451-principles-of-digital-communication-ii-spring-2005/resources/mit6_451s05_fulllecnotes/)

#### Textbooks

1. R. M. Roth, [Introduction to Coding Theory](https://www.cambridge.org/core/books/introduction-to-coding-theory/377D24BE73F473B15378776B0AE63CA3), Cambridge University Press, 2006.
2. W. C. Huffman and V. Pless, [Fundamentals of Error Correcting Codes](https://www.cambridge.org/core/books/fundamentals-of-errorcorrecting-codes/BF3AFDFB539C3C023BBD9DCBA4CDA761), Cambridge University Press, 2003.
3. F. J. MacWilliams and N. J. A. Sloane, The Theory of Error-Correcting Codes, Elsevier/North-Holland, 1977. 
