# PrimeNumber
Program to find the Prime Number.

Explanation:
============

* The program begins with the declaration of the package org.javainterview.

* Next, the PrimeNum class is defined. This class contains the logic to determine whether a given number is prime or not.

* Inside the PrimeNum class, there is a private method called num(). This method is responsible for taking input from the user, performing the prime number check, and displaying the result.

* Within the num() method, a Scanner object named scan is created to read input from the user.

* The program prompts the user to enter a number by displaying the message "Enter the number: ".

* The entered number is read using the nextInt() method of the Scanner class and stored in the num variable of type int.

* Two additional variables are declared: count, initialized to 0, and i, which is used as a loop counter.

* A for loop is used to iterate from 1 to the entered number (num).

* Inside the loop, an if statement checks whether num is divisible evenly by i. If the condition is true, it means that i is a factor of num, and the count variable is incremented by 1.

* After the loop finishes, the program checks whether count is equal to 2. If count is equal to 2, it means that the number has only two factors (1 and itself), and thus it is prime. In this case, the program displays the message "Its a Prime number.".

* If count is not equal to 2, it means the number has more than two factors, and it is not prime. The program displays the message "Its not a Prime number.".

* The main method is declared, which is the entry point of the program.

* Inside the main method, an instance of the PrimeNum class is created using the statement PrimeNum info = new PrimeNum();.

* The num() method is called on the info object to start the prime number check process.

* The program execution ends.

==> In summary, this program prompts the user to enter a number, checks whether the number is prime or not, and displays the result accordingly. <==
