## Merge join 

Having two sorted files(in our case R_sorted.tsv and S_sorted.tsv) and WITHOUT loading all this files in memory we read them line by line and perform merge join.
E.g R_sorted = ['aa', 33], S_sorted = ['aa', 45] the output will be ['aa', 33, 45]
