Sorting
=======
In this assignment you will write a program that tests 4 different sorting algorithms: Bubble, Selection, Insertion, and Merge sort. You will write a `Stopwatch` class that uses `System.nanoTime()` to measure the time each algorithm takes to sort 1000, 2000, 4000, and 8000 integers.

Suggested steps to complete this assignment
-------------------------------------------

1. Fork and clone down this repository.
2. Run the program. You should see the following output:  
Testing Bubble Sort  
Bubble Sort took 0 microseconds  
Testing Selection Sort  
Selection Sort took 0 microseconds  
Testing Insertion Sort  
Insertion Sort took 0 microseconds  
Testing Merge Sort  
Merge Sort took 0 microseconds   
3. First, use `System.nanoTime()` to complete the `Stopwatch` class 
4. Then, starting with `bubblesort`, complete the 4 sorting functions in the `Sorts` class
5. (Note that you do not need to add any code to the `SortStep` program)
6. Test each sorting algorithm for the time it takes to sort 1000, 2000, 4000 and 8000 integers, and write your answers on the handout for the assignment. You should run the tests several times and record the best time for each. You can change the number of integers by changing the initialization of the `private` `numInts` variable in `SortStep.pde`.
7. When you are finished, submit the sorting handout to the schoolloop drop box. (Note that is not necessary to submit your code for the assignment).
8. If you have extra time, you might try to improve the efficiency of your merge sort. Also, feel free to add other sorts like quick sort or gnome sort to the program.



The time it took me for 1000:
Testing Bubble Sort
Bubble Sort took 10124 microseconds
Testing Selection Sort
Selection Sort took 8678 microseconds
Testing Insertion Sort
Insertion Sort took 8397 microseconds
Testing Merge Sort
Merge Sort took 5867 microseconds

The time it took me for 2000:

Testing Bubble Sort
Bubble Sort took 14530 microseconds
Testing Selection Sort
Selection Sort took 10797 microseconds
Testing Insertion Sort
Insertion Sort took 10548 microseconds
Testing Merge Sort
Merge Sort took 27547 microseconds

The time it took me for 4000:

Testing Bubble Sort
Bubble Sort took 39730 microseconds
Testing Selection Sort
Selection Sort took 19141 microseconds
Testing Insertion Sort
Insertion Sort took 20368 microseconds
Testing Merge Sort
Merge Sort took 51497 microseconds


The time it took me for 8000:

Testing Bubble Sort
Bubble Sort took 131051 microseconds
Testing Selection Sort
Selection Sort took 50008 microseconds
Testing Insertion Sort
Insertion Sort took 55174 microseconds
Testing Merge Sort
Merge Sort took 154680 microseconds
