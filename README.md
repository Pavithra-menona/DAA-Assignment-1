# DAA-Assignment-1
# Insertion Sort Algorithm

## Objective

Implement the Insertion Sort algorithm and analyze its time and space complexities.

---

## Programming Language

Python

---

## Algorithm

1. Start from the second element.
2. Store the current element as the key.
3. Compare the key with previous elements.
4. Shift larger elements one position to the right.
5. Insert the key at the correct position.
6. Repeat until the array is sorted.

---

## How to Run

1. Install Python 3.

2. Open terminal.

3. Execute:

```bash
python insertion_sort.py
```

4. Enter the number of elements.

5. Enter the array elements.

6. View the sorted output.

---

## Sample Input

```
6
64
25
12
22
11
90
```

---

## Sample Output

```
11 12 22 25 64 90
```

---

## Time Complexity

| Case | Complexity |
|------|------------|
| Best | O(n), Θ(n), Ω(n) |
| Average | O(n²), Θ(n²), Ω(n²) |
| Worst | O(n²), Θ(n²), Ω(n²) |

---

## Space Complexity

```
O(1)
```

---

## Advantages

- Simple to implement.
- Efficient for small datasets.
- Stable sorting algorithm.
- In-place sorting.

---

## Disadvantages

- Inefficient for large datasets.
- Time complexity becomes O(n²) for average and worst cases.

---

## Course Outcome

CO1 – Analyze any given algorithm and express its time and space complexities using asymptotic notations.
