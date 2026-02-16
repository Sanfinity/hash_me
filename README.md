# This is my hash table implementation from scratch in c programming language


Code structure
Code should be laid out in the following directory structure.

.
├── build
└── src
    ├── hash_table.c
    ├── hash_table.h
    ├── prime.c
    └── prime.h
src will contain our code, build will contain our compiled binaries.


Terminology
There are lots of names which are used interchangeably. In this article, we'll use the following:

Associative array: an abstract data structure which implements the API described above. Also called a map, symbol table or dictionary.

Hash table: a fast implementation of the associative array API which makes use of a hash function. Also called a hash map, map, hash or dictionary.

Associative arrays can be implemented with many different underlying data structures. A (non-performant) one can be implemented by simply storing items in an array, and iterating through the array when searching. Associative arrays and hash tables are often confused because associative arrays are so often implemented as hash tables.