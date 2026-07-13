---
layout: page
title: Priv-2026
permalink: /2026-Jul-Priv
---

## EE6180: Data Privacy (Jul.--Nov. 2026)

**Instructor**: [Arvind Rameshwar](arvindrameshwar.github.io)

**Time and Location**: Mondays (14:00--15:15 hours), Tuesdays (15:30--16:45 hours), and (infrequent) special sessions on Thursdays (17:00--17:50 hours)
                       at ESB-350. The first class is on Monday, 27 July 2026.
                       
**Office Hours**: Thursdays (15:00--16:00 hours); do send me an email in advance

### Course Description

In this course, we shall study algorithms for provably protecting the privacy of individuals participating in data mining tasks (think: the potentially sensitive information mined from you when you visit websites, or when you visit your doctor, or when you provide details during a population census). The course assumes significance in the face of the now-well-known GDPR law (of the EU) and the CCPA and HIPAA regulations (of the USA), and the DPDP Act, which is soon to come into effect in India. Trained privacy engineers/data scientists will hence be sought after; the tools introduced in this course are towards this end.

In particular, this edition of the course will focus on differential privacy (DP) -- the "gold standard" for measuring privacy guarantees. The course will be organized around the following five (unequal) parts:

1. **Attacks on privacy**: How can one extract sensitive information from aggregate queries?
2. **DP and its properties**: What is DP and how do we realize it (more or less universally) for any statistics release task?
3. **Specialized DP mechanisms for statistics release**: Given information on the statistic of interest to be released, can we design fine-tuned private algorithms that allow accurate statistic reconstruction?
4. **Introduction to private ML**: Is there a general approach for augmenting common steps in machine learning tasks with privacy-preserving measures?
5. **DP in practice**: Where has DP been employed in the real world by governments/big tech firms and what are the technical challenges involved?

### Prerequisites

Comfort with basic linear algebra and probability, in addition to familiarity with understanding and writing mathematical proofs.

### Tentative List of Topics

Re-identification and reconstruction attacks, privacy heuristics (k-anonymity and $\ell$-diversity), DP definition and properties (composition, group privacy, post-processing), approximate DP, Laplace and Gaussian mechanisms, exponential mechanism, binary tree mechanism, sparse-vector/AboveThreshold technique, private empirical risk minimization and private gradient descent, DP for real-world data mining tasks, local DP, post-processing for consistency

### Grading

There will be three examinations: two midterms and a final, and a collection of take-home assignments. The exams will closely follow the course material, and the take-home assignments are meant to supplement and extend the lectures.

* Midterms: 50% (25% each)
* Project presentation: 40%
* Class participation: 10%

### Schedule

Handwritten lecture notes will be made available at the end of every module.

### Selected Useful Online Courses and References

#### Courses

1. Prof. Adam Smith's course at Boston University: [Privacy in Statistics and Machine Learning, Spring 2025](https://dpcourse.github.io/2025-spring/schedule.html)
2. Prof. Raef Bassily's course at Ohio State University: [CSE 5479: Privacy-Preserving Machine Learning, Fall 2018](https://sites.google.com/view/rbassily/teaching/previous-classes/privacy-preserving-machine-learning-cse5479-fall-2018)
3. Prof. Gautham Kamath's course at the University of Waterloo: [CSE 860: Algorithms for Private Data Analysis, Fall 2020](http://www.gautamkamath.com/CS860-fa2020.html)

#### Textbooks

1. C. Dwork and A. Roth, [The Algorithmic Foundations of Differential Privacy](https://www.cis.upenn.edu/~aaroth/Papers/privacybook.pdf), Foundations and Trends in Theoretical Computer Science, Vol. 9, Nos. 3–4 (2014), 211–407, 2006.
2. S. Vadhan, [The Complexity of Differential Privacy](https://privacytools.seas.harvard.edu/sites/g/files/omnuum6656/files/privacytools/files/complexityprivacy_1.pdf), Lindell, Y. (eds) Tutorials on the Foundations of Cryptography, Information Security and Cryptography, Springer, Cham, 2017.
3. J. P. Near and C. Abuah, [Programming Differential Privacy](https://programming-dp.com/), Vol. 1, 2021.
