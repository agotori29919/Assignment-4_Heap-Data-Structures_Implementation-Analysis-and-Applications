Heap Sort Algorithm

Instructions to Run the Code
Running Heapsort
The Heapsort algorithm is implemented in the heapsort function. 
You can run this function with any list of integers to see the sorted output.

Requirements:-
Python 3

Steps:-
1. Open the Python file (Assignment 4_Heapsort_algorithm.py).
2. Run the file using a Python interpreter.
3. Expected Output 
Original array: [21, 11, 15, 4, 6, 7]
Sorted array: [4, 6, 7, 11, 15, 21]


Findings:-
All Heapsort cases best, average and worst = O(n log n) time. This is due to building the max-heap and repeatedly extracting the maximum element while restoring heap property.

Space Complexity
Heapsort, an in-place sorting algorithm, requires only O(1) space beyond the input array.

Usage
Heapsort is useful when memory space is limited and stable sorting is unnecessary.



Priority Queue & Scheduler

1. Open the Python file which has Priority Queue & Scheduler in one code. (Assignment 4_Priority Queue.py).
2. Run the file using a Python interpreter.
3. Expected Output

Priority Queue Simulation:
Initial tasks in the queue: [Task(ID: 3, Priority: 20, Arrival: 2, Deadline: 10), Task(ID: 4, Priority: 15, Arrival: 3, Deadline: 6), Task(ID: 1, Priority: 10, Arrival: 0, Deadline: 5), Task(ID: 2, Priority: 5, Arrival: 1, Deadline: 7)]
Processing task with highest priority: Task(ID: 3, Priority: 20, Arrival: 2, Deadline: 10)
Processing task with highest priority: Task(ID: 4, Priority: 15, Arrival: 3, Deadline: 6)
Processing task with highest priority: Task(ID: 1, Priority: 10, Arrival: 0, Deadline: 5)
Processing task with highest priority: Task(ID: 2, Priority: 5, Arrival: 1, Deadline: 7)

Findings:-
Priority Queue
To implement the priority queue a Python list is employed. The task priority value is used to prioritize the tasks with the highest priority task which are to be processed first.

This priority queue could be used in real world applications like - scheduling where tasks are need to be processed based on their priority.

Scheduler Simulation
The scheduler simulation shows the process of adding tasks to a priority queue and processing them according to their priority. This emphasizes the practical application of priority queues in order to prioritize tasks in task scheduling and other real-time systems that require task prioritization.




