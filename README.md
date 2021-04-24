# page-replacement-algorithms-FIFO-LRU-OPT
Assumption: The data will be entered in the following way
Futurer function tells which page will be last used in the future
The program solves for:
First In First Out Page Replacement Algorithm (FIFO)
Optimal Page replacement Algorithm (OPT)
Least Recently Used Page replacement Algorithm (LRU)

Also for the FIFO it finds out Belady's Anomaly



Here is the input output list for the first question:



(base) netrunner@dew:~/Desktop/sem 7/ass6$ g++ -o test ass6.cpp
(base) netrunner@dew:~/Desktop/sem 7/ass6$ ./test
Enter number of iterations: 3
Enter the number of frames allocated: 3
Enter the reference string: 321032432104
Faults using FIFO: 9
Faults using LRU: 10
Faults using OPT: 5
Enter the number of frames allocated: 4
Enter the reference string: 321032432104
Faults using FIFO: 10
Faults using LRU: 8
Faults using OPT: 5
Enter the number of frames allocated: 5
Enter the reference string: 321032432104
Faults using FIFO: 5
Faults using LRU: 5
Faults using OPT: 5
Belady Anomaly detected
(base) netrunner@dew:~/Desktop/sem 7/ass6$ ^C
