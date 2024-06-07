
# Shell Script Assignments

## Assignment 1 : Basic Programs

- Write a shell script to create a menu driven calculator that will accept 2 numbers num1 and num2 and the following options:-
    - 1 -> Addition, 2 -> Subtraction, 3 -> Multiplication
    - 4 -> Division, 5 -> Modulo, 6 -> Reenter numbers
    - 7 -> Exit
    - In case option not lying between 1 to 7 is chosen by the user, then print -> "Invalid option. Please try again."

- Write a shell script to find the square roots of a quadratic equation ax^2 + bx + c given the inputs are a,b and c. Print the following log statement in the following cases as per the suitable scenario.
    - Print "Roots are real and different". Print root1, root2
    - Print "Roots are real and equal". Print root1
    - Print "Roots are complex and different". Print root1, root2

## Assignment 2 : Numbers

- Write a shell script to find the maximum between three numbers. The script should take three arguments from the command line, compare them, and print the larger of the three numbers.

    - Input: ./max3_number.sh 5 10 15
    - Output: 15

- Write a shell script to compute the sum of the first \( n \) natural numbers, where \( n \) is a given natural number. The algorithm should take \( n \) as input and output the sum of all natural numbers from 1 to \( n \). 

    - Input: 5 
    - Output: 15 

- Write a shell script to determine whether a given number is a prime number. The script should take a single integer input and output whether the number is prime or not.
    
    - Input: ./prime_check.sh 29 
    - Output: 29 is a prime number

- Write a shell script named prime_factors.sh that takes a positive integer from the user and prints its prime factors.

```
$ ./prime_factors.sh
Enter a positive integer: 36
Prime factors of 36 are: 2 2 3 3
```

- Write a shell script to check whether a given number is a perfect number or not. A perfect number is a positive integer that is equal to the sum of its proper divisors, excluding itself.

    - Input: ./perfect_check.sh 28
    - Output: The number 28 is perfect.

- Write a shell script to check whether a given number is a palindrome. The script should take a number as input and output whether the number is a palindrome or not. A palindrome number reads the same backward as forward.

    - Input: "Enter the number: 12321"
    - Output: 12321 is a palindrome.

- Write a shell script to find the Greatest Common Divisor (GCD) and Least Common Multiple (LCM) of two numbers provided by the user.

    - Input:  
        num1 = 24  
        num2 = 36
    - Expected Output:  
        GCD of 24 and 36 is 12  
        LCM of 24 and 36 is 72

- Write a shell script to generate the Fibonacci series based on the number of terms provided as input. The script should prompt the user to enter the number of terms (terms) and then output the Fibonacci series containing that number of terms. 

```
$ ./fibonacci_sequence.sh
Enter a non-negative integer: 8
Fibonacci sequence: 0 1 1 2 3 5 8 13
```

Ensure your script handles both positive and non-positive integer inputs gracefully. Additionally, test the script with edge cases such as 0 and negative numbers to ensure robustness.`

- Write a shell script to calculate the factorial of a given positive number. The script should prompt the user to enter a positive integer and output its factorial. Ensure that the script handles invalid inputs gracefully.

    - Input: 5
    - Output: Factorial of 5 is 120

- Write a shell script named "armstrong_check.sh" that takes an integer as input and determines whether it is an Armstrong number or not. An Armstrong number is a number that is equal to the sum of its own digits each raised to the power of the number of digits.

    - Test Case 1:  
        Input: 370  
        Expected Output: 370 is an Armstrong number.
    - Test Case 2:  
        Input: 123  
        Expected Output: 123 is not an Armstrong number.

- Write a shell script named largest_sum_subarray.sh that takes an array of integers as input and prints the contiguous subarray with the largest sum.

```
$ ./largest_sum_subarray.sh
Enter space-separated integers: -2 1 -3 4 -1 2 1 -5 4
Largest sum subarray: 4 -1 2 1
```

## Assignment 3 : Strings

- Write a shell script named string_reverse.sh that takes a string from the user and prints its reverse.

    - Test Case 1:  
        Enter a string: hello  
        Reversed string: olleh  

- Write a shell script named `file_processing.sh` that performs the following tasks:
```    
    1. Accepts a directory path from the user.
    2. Checks if the directory exists. If not, prints an error message and exits.
    3. Lists all the files in the directory and its subdirectories recursively.
    4. For each file, extracts its extension and counts the number of occurrences of each unique extension.
    5. Prints a summary showing each unique extension along with the count of files having that extension.
```

```bash
$ ./file_processing.sh
Enter directory path: /home/user/documents

Summary:
- txt: 10 files
- pdf: 5 files
- docx: 3 files
- jpg: 7 files
- png: 2 files
- others: 4 files
```

- Write a shell script named word_frequency.sh that takes a text file as input and prints the frequency of each word in the file, sorted by frequency in descending order.

```
$ ./word_frequency.sh
Enter the path of the text file: sample.txt

Word Frequency:
5 hello
3 world
2 shell
1 script
1 example
```

- Write a shell script named backup_files.sh that takes a directory path as input and creates a compressed backup of all files in the directory and its subdirectories, excluding directories.

```
$ ./backup_files.sh
Enter the directory path: /home/user/documents

Backup created: backup_20240607_150205.tar.gz
```

- Write a shell script named string_compression.sh that takes a string as input and prints the compressed version of the string.

```
$ ./string_compression.sh
Enter a string: aabcccccaaa
Compressed string: a2b1c5a3
```
