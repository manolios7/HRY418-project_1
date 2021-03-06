# Parallelized-Humming-distance

Parallelize a simple program using openMP and pthreads, in C. Use the script to compile and run all the files.

The program creates two equally sized arrays containing random strings. Then, it computes a 2D matrix with the Hamming distances between the strings in the same positions on the two previous arrays. Finally, it times the computational part.

Benchmarked on dual Intel Xeons E5620 @ 2.40GHz with 8GB DDR3 memory.

## Parallelization

For each parallelization method, three different granularities have been requested. Total 7 implementations (3 OpenMP, 3 pthreads, 1 serial). Only the computational part has been paralleled. The task sizes are a line of strings, a string or a character.


## Script Variables

'A' and 'B' are the size of the arrays, 'LENGTH' is the size of the strings and 'THREADS' is the number of the threads that will be used in the parallel implementations.
