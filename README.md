# 1913153_TanyaArora

## This is my Data Mining and Warehousing Assignment 1

APRIORI ALGORITHM USING PYTHON: 

## Apriori Algorithm
Apriori algorithm assumes that any subset of a frequent itemset must be frequent.
Say, a transaction containing {wine, chips, bread} also contains {wine, bread}. So, according to the principle of Apriori, if {wine, chips, bread} is frequent, then {wine, bread} must also be frequent.
The key concept in the Apriori algorithm is that it assumes all subsets of a frequent itemset to be frequent. Similarly, for any infrequent itemset, all its supersets must also be infrequent.

## Principle of Apriori Algorithm: 
If an itemset is infrequent, then all of its supersets must also be infrequent

### The minimum support given is - 20%

### Final Frequent Set
[('t1', 't5', 't6'), ('t2', 't5', 't6'), ('t4', 't5', 't6')]
