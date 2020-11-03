---
title: "Indexing weighted sequences: Neat and efficient"
collection: publications
permalink: /publication/2020-02-02-paper-title-number-6
excerpt: 'A weighted sequence is a sequence of probability mass functions over a finite alphabet. We present applications of our weighted index, in particular in approximate and general scenarios that were introduced by Biswas et al. (2016), and provide its implementation.'
date: 2020-02-02
venue: 'Information and Computation'
paperurl: 'https://research.vu.nl/en/publications/indexing-weighted-sequences-neat-and-efficient'

---
The cornerstone of our data structure is a novel construction of a family of z special strings that carries the information about all the strings that occur in the weighted sequence with a sufficient probability. We obtain a weighted index with the same complexities as in the most efficient previously known index by Barton et al. (CPM 2016), but our construction is significantly simpler. The most complex algorithmic tool required in the basic form of our index is the suffix tree which we use to develop a new, more straightforward index for the so-called property matching problem. We provide an implementation of our data structure. Our construction allows us also to obtain a significant improvement over the complexities of the approximate variant of the weighted index presented by Biswas et al. (EDBT 2016) and an improvement of the space complexity of their general index.
