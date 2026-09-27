# Merge Sort and Quick Sort – C Programming Assignment

## 📌 About the Assignment

This assignment implements and compares two sorting algorithms using C:

- Merge Sort
- Quick Sort

The algorithms are applied to the following fixed-length IDs:

```text
324, 125, 456, 218, 102, 389, 275, 147
Objectives
Implement Merge Sort in C.
Display the array after each merge operation.
Implement Quick Sort in C.
Display the important partition results.
Display the final sorted sequence.
Compare Merge Sort and Quick Sort based on:
Number of passes/partitions
Number of comparisons
Time complexity
Additional space
🔢 Input
324 125 456 218 102 389 275 147
✅ Output

The final sorted sequence is:

102 125 147 218 275 324 389 456
⚙️ Algorithms
Merge Sort

Merge Sort uses the Divide and Conquer technique.

Time Complexity:

Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)

Additional Space: O(n)

Quick Sort

Quick Sort uses the Divide and Conquer technique by selecting a pivot and partitioning the array.

Time Complexity:

Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n²)

Additional Space:

Average Case: O(log n)
Worst Case: O(n)
📊 Comparison
Feature	Merge Sort	Quick Sort
Best Case	O(n log n)	O(n log n)
Average Case	O(n log n)	O(n log n)
Worst Case	O(n log n)	O(n²)
Extra Space	O(n)	O(log n) Average
Main Operation	Merge	Partition
💻 Language Used

C Programming

▶️ How to Run

Compile the program using GCC:

gcc sorting.c -o sorting

Run the program:

./sorting
📁 Files
sorting.c    - C program containing Merge Sort and Quick Sort
README.md    - Assignment documentation
👨‍🎓 Student

Melvin Biju Philip

B.Tech – Artificial Intelligence and Data Science


This version is **short, clean, and appropriate for a college GitHub assignment**.

Available next action: :contentReference[oaicite:0]{index=0}
