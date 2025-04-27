                                     **Sorting Algorithms Performance Analysis**
                                     
This project analyzes the performance (execution time) of four classic sorting algorithms:

Bubble Sort

Selection Sort

Insertion Sort

Merge Sort

The program measures the average time taken by each algorithm to sort arrays of different sizes, and then plots the results for visualization.

Project Structure
Each algorithm is handled in a separate section:

1. Bubble Sort
Function: bubble_sort(arr)

Sorts the array using the basic bubble sort approach.

Measures average execution time across 5 runs.

Prints the sorted arrays and average times.

Plots input size vs. average time.

2. Selection Sort
Function: selection_sort(arr)

Sorts by repeatedly selecting the minimum element.

Measures and prints performance as above.

Separate plot for selection sort.

3. Insertion Sort
Function: insertion_sort(arr)

Sorts the array by inserting elements into their correct position.

Measures and displays timing results.

Graph for insertion sort.

4. Merge Sort
Function: merge_sort(arr)

Uses divide and conquer strategy to sort.

Measures and prints sorting times.

Separate plot for merge sort.

Common Method
Each sorting section shares:

A measure_time(sort_function, arr) function to measure average execution time over 5 runs.

Arrays of different input sizes:

5 elements

10 elements

50 elements

100 elements

Matplotlib (matplotlib.pyplot) is used for plotting graphs.

Requirements
Python 3.x

Libraries:

matplotlib

time (standard library)

You can install matplotlib using:


pip install matplotlib
How to Run
Simply run the Python script. It will:

Sort arrays using each algorithm

Print sorted arrays

Print average execution times

Display a plot showing performance for each sorting technique

Example Output
Console Output:


Sorted array of size 5: [1, 2, 3, 4, 5]
Sorted array of size 10: [1, 2, ..., 10]
...
Average Execution Times:
Input size 5: 0.00000314 seconds
Input size 10: 0.00000521 seconds
...
Graph Example:

X-axis: Input size (number of elements)

Y-axis: Average execution time (seconds)

Each algorithm has a separate graph with different colors.

Notes
The arrays are already sorted (1 to N). Therefore, some sorting algorithms (like Insertion Sort) perform better than they would on random data.

For more realistic benchmarking, you can modify the arrays to contain random elements.
