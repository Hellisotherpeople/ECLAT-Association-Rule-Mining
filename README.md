# ECLAT-Association-Rule-Mining
An implementation of the Equivalence Class Transformation Association Rule Mining algorithim in Python

I wrote this while I was bored and looking for a good algorithim to speed up with Cython. Unfortunately, this problem doesn't lend itself to being optimized so easily (and the FP-tree method of frequent pattern mining is much faster).

This algorithim is still pretty fast on the sorts of datasets that it excels on (a store that sells 10 items with 1 million records) but on a dataset of 1000 items with 1000 records it will chugg

My work is messy. Maybe I'll go back and clean it up one day. 
