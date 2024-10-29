# Week44-Pointers

Hello students! I saw that you were requesting tasks that teach you the use case of pointers, so that is what you will be working on this week. There is no need to download this github repository, instead you will make your own Visual Studio solution and project and code your answer to the tasks described.

## Setup
Create a class which holds a public integer. The integer is set in the class's constructor.

## Task 1
In another file such as main:

Create a function which takes your class made in the setup as its parameter, and print's the integer.

## Task 2
Create a function which takes an array of integers as its parameter along with the size of the array. This function prints every integer in the array.

## Task 3
Take task2 but add an & in front of the integer printed. like if i had a int arr[0] it would be &arr[0]

## Task 4
Create a function which takes an array of the class you made as its parameter along with the size of the array. This function calls the print function of the class.

## Task 5
Same as task 4, but add an & in front of the integer printed. like MyClass.MyInt will be &MyClass.MyInt. remember to have the integer be public

## Task 6

Create the function `void PassByReference(int &i)`.
which changes the value of i inside the function.


in main, create an integer variable and print it.

pass the integer variable to PassByReference function.

print the variable again.


If you want to learn what we did in task 6, [you can read about it on IBM's website](https://www.ibm.com/docs/en/i/7.1?topic=calls-pass-by-reference)
