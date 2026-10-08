# dsa-python

Data structures and algorithms in Python 3, solved by pattern as part of a 12-week interview plan (October 2026 to January 2027).

Every solution starts with a short note: the approach in plain words, time and space complexity, and whether it was solved without help.

## Progress by pattern

| Folder | Pattern | Solved |
| --- | --- | --- |
| [`01-arrays-hashing`](01-arrays-hashing/) | Arrays & hashing | 0 / 7 |
| [`02-two-pointers`](02-two-pointers/) | Two pointers | 0 / 5 |
| [`03-sliding-window`](03-sliding-window/) | Sliding window | 0 / 5 |
| [`04-stack`](04-stack/) | Stack | 0 / 6 |
| [`05-binary-search`](05-binary-search/) | Binary search | 0 / 6 |
| [`06-linked-list`](06-linked-list/) | Linked list | 0 / 7 |
| [`07-trees`](07-trees/) | Trees | 0 / 10 |
| [`08-heaps`](08-heaps/) | Heaps | 0 / 4 |
| [`09-backtracking`](09-backtracking/) | Backtracking | 0 / 6 |
| [`10-tries`](10-tries/) | Tries | 0 / 3 |
| [`11-graphs`](11-graphs/) | Graphs (DFS, BFS, topological sort, union-find) | 0 / 9 |
| [`12-advanced-graphs`](12-advanced-graphs/) | Advanced graphs (shortest paths, minimum spanning tree) | 0 / 5 |
| [`13-1d-dp`](13-1d-dp/) | 1-D dynamic programming | 0 / 9 |
| [`14-2d-dp`](14-2d-dp/) | 2-D dynamic programming | 0 / 6 |
| [`15-intervals-greedy`](15-intervals-greedy/) | Intervals and greedy | 0 / 9 |
| [`16-bit-manipulation`](16-bit-manipulation/) | Bit manipulation | 0 / 5 |
| [`17-math-matrix`](17-math-matrix/) | Math and matrix | 0 / 4 |
| [`structures`](structures/) | Data structures written from scratch, with tests | 0 / 7 |

106 problems in total, drawn from the Blind 75 and NeetCode 150 lists. Each folder's README lists its problems with links.

## How each solution is written

1. Copy [`TEMPLATE.py`](TEMPLATE.py) into the pattern's folder and name it after the problem, in snake_case.
2. Fill in the header: link, approach, complexity, solved alone or not.
3. Add a few asserts under `if __name__ == "__main__":` and run the file.

## Running

```bash
python 01-arrays-hashing/two_sum.py
```

Tests with pytest and a GitHub Actions workflow are added in week 1.
