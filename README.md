# super30-python-loop-task-2

Question 1: Skip Numbers Divisible by 5 (1–100)

Approach: Iterated through the range 1 to 100 using a for loop. Inside the loop, applied the modulo operator i % 5 == 0 with a continue statement to bypass printing whenever a number is a multiple of 5.

Question 2: Terminate Loop at First Common Multiple of 7 and 11

Approach: Looped from 1 to 100 and evaluated if the current number satisfies both i % 7 == 0 and i % 11 == 0. Used a break statement to halt iteration immediately once the first multiple (77) is encountered.

Question 3: Search an Element in a List using for-else

Approach: Iterated sequentially across the list to compare each element with the target user input. If a match is found, the loop prints the confirmation and terminates via break; otherwise, the else block executes after the loop finishes without breaking.

Question 4: Indexed Traversal with enumerate()

Approach: Used a for loop combined with enumerate(names, start=1) to traverse the collection and retrieve both the 1-based sequential rank and the corresponding string simultaneously.

Question 5: Right-Angled Star Pattern

Approach: Implemented nested for loops. The outer loop controls the row count from 1 to 5, while the inner loop iterates up to the current row index i to print asterisks incrementally on each line.

Question 6: Inverted Star Pattern

Approach: Used nested loops where the outer loop steps backward from 6 down to 2 (step=-1). The inner loop prints asterisks corresponding to the decreasing row count to produce an inverted triangle.

Question 7: Multiplication Tables (1 to 10)

Approach: Structured with nested loops. The outer loop cycles through numbers 1 to 10 representing each table, and the inner loop iterates through multipliers 1 to 10 to compute and display formatted products.

Question 8: Common Multiples of 3 and 5 (1–200)

Approach: Traversed the sequence from 1 to 199 using a for loop. Checked for simultaneous divisibility by 3 and 5 (i % 3 == 0 and i % 5 == 0) before printing valid multiples.

Question 9: Remove Duplicates Without set()

Approach: Initialized an empty list and iterated over the original collection item-by-item using a for loop. Evaluated membership with not in before appending, preserving first-seen order while filtering out duplicates.

Question 10: Count Positives, Negatives, and Zeros

Approach: Initialized three independent counter variables to zero. Looped through each element in the list and incremented the respective counter using an if-elif-else conditional structure.

Question 11: Single Number Primality Test

Approach: Iterated potential divisors from 2 up to number - 1. If any value divides the input evenly (number % i == 0), the number is flagged as non-prime and the loop breaks; if no divisors are found, the else block validates the number as prime.

Question 12: Prime Generation Across a Range (1–100)

Approach: Implemented nested loops with for-else. The outer loop iterates through numbers 2 to 99, while the inner loop checks for factors up to num // 2 + 1. If no factor divides the candidate evenly, the inner else block prints the prime number.

