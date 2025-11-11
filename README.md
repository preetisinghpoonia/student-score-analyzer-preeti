# student-score-analyzer-preeti
this is a student score analyzer in c for jecrc
This C program is designed to analyze students' scores by computing the class average, highest, and lowest scores using user-defined functions.
It begins with the inclusion of the standard input-output header file stdio.h, which provides the necessary functions for input and output operations. 
The program defines three separate functions to make the code modular and easier to understand. 
The first function, findMean(), takes an array of student scores and the total number of students as input, then calculates the mean by summing all the scores using a loop and dividing the total by the number of students. 
The second function, findHighest(), identifies the highest score in the given array by iterating through each score and comparing it with the current highest value, updating it whenever a larger score is found. Similarly, the third function, findLowest(), determines the lowest score by comparing each element with the current lowest value and updating it when a smaller score appears. 
In the main() function, the program first asks the user to enter the number of students, with a suggested limit of 10, to prevent exceeding a manageable array size. 
It then prompts the user to input each student’s score, storing them sequentially in an integer array named scores. 
After collecting all the scores, the program calls the three previously defined functions to compute the mean, highest, and lowest scores and stores the returned values in the variables mean, highest, and lowest. 
Finally, it displays a formatted class report showing the class average (rounded to two decimal places), the highest score, and the lowest score. 
This structured approach demonstrates the use of arrays, loops, functions, and formatted output in C, which are fundamental concepts in modular programming and data processing.
