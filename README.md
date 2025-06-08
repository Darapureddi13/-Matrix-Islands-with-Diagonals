# -Matrix-Islands-with-Diagonals
Description
This program counts the number of islands in a 2D matrix where islands are groups of adjacent 1s connected horizontally, vertically, or diagonally.

Requirements
Python 3.x

No external dependencies

How to Run
Save the code to a file (e.g., island_counter.py)

Run the script:

bash
python island_counter.py
Usage
The main function count_islands() takes a 2D matrix as input and returns the island count:

python
matrix = [
    [1, 0, 1],
    [0, 1, 0],
    [1, 0, 1]
]
print(count_islands(matrix))  # Output: 5
Algorithm
Time Complexity: O(rows × cols)

Space Complexity: O(rows × cols) (due to recursion stack)

Test Cases
The code includes 4 test cases covering:

Single island

Multiple diagonal islands

No islands

One large connected island

Example Output
text
Test 1 - Expected: 2, Actual: 2
Test 2 - Expected: 5, Actual: 5
Test 3 - Expected: 0, Actual: 0
Test 4 - Expected: 1, Actual: 1
