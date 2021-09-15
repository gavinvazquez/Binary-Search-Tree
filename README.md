# Binary-Search-Tree
This program gains familiarity with using binary search trees by implementing a variety of functions.

# Functions Implemented
find(): Return a pointer to the node with key k in tree T, or nullptr if it doesn't exist

select(): Return pointer to node of rank r (with r'th largest key; e.g. r=0 is the minimum)

join(): Join trees L and R (with L containing keys all <= the keys in R); return a pointer to the joined tree.

remove(): Remove key k from T, returning a pointer to the resulting tree; it is required that k be present in T

split(): Split tree T on key k into tree L (containing keys <= k) and a tree R (containing keys > k)

insert_random(): Insert key k into the tree T, returning a pointer to the resulting tree. If k is the Nth node inserted into T, then: with probability 1/N, insert k at the root of T, otherwise, insert_random k recursively left or right of the root of T
