# Sorting and Scheduling Algorithms

A small collection of Python scripts demonstrating classic algorithm techniques: sorting performance analysis and greedy resource assignment.

## Contents

### `task1.py` — QuickSort Benchmark

Compares two QuickSort variants on randomly generated integer arrays:

- **Deterministic QuickSort** — always selects the middle element as the pivot.
- **Randomized QuickSort** — selects a random element as the pivot.

For each array size (10,000 / 50,000 / 100,000 / 500,000 elements), both algorithms are run 5 times and the average execution time is measured and plotted with `matplotlib`.

### `task2.py` — Greedy Teacher Scheduling

Assigns teachers to subjects using a greedy algorithm. At each step it selects the teacher who can cover the most remaining subjects (ties broken by youngest age), repeating until every subject is covered or no valid assignment remains.

## Stack

- Python 3
- `matplotlib` (for `task1.py`)

## Usage

```bash
pip install matplotlib
python task1.py
python task2.py
```
