# Multithreaded Merge Sort

Merge sort in C that splits the work across several POSIX threads.

## Configuration

- `N`: how many random numbers are generated for testing.
- `merge_sort_mt(start, len, 4);`: the third argument is the number of threads (4 here).

## Running

```bash
gcc main.c -o mergesort -pthread
./mergesort
```

## Notes

Creating, synchronising and joining threads has a cost. For small inputs, a single-threaded sort is faster, so this approach only pays off on large data sets.
