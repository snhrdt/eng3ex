# Basic Java programming exercises

## General requirements

1. Work in this repository only; do not fork it. This is a private repository for only you, the applicant, and me as the reviewer.
2. For each of the following exercises, create a folder and develop your solution inside this folder. Each solution should have one executable Main class; you can use additional classes as you see fit.
3. Unless otherwise stated, you can use all classes, interfaces, enums etc. of the Java 11 SDK. Do **not** use any additional libraries.
4. Each solution to an exercise needs to be independent of the other solutions and should be easily runnable by executing the Main class: `java Main`.
5. If there are one or more additional questions in an exercise, copy them to a `README.md` file in the solution folder and answer them in this file.

## Exercises

### foobar

Implement a Java program that loops over all integers from 0 to 100. Each integer shall be printed on a new line. If the integer is divisible by 7 but not by 3, a space followed by the string `foo` shall be printed after the integer. If the integer is divisible by 7 and 3, a space followed by the string `foobar` shall be printed after the integer. For integers divisible by 3 but not by 7, a space followed by the string `bar` shall be printed after the integer.

Try to optimize the code to use the least amount of comparisons during its execution, and describe in the `README.md` what you did.

### Stream processing

Consider the following employee data:

|Name|Age|Salary|Office|
|---|---|---|---|
|Andrew|32|65000|LA|
|Beatrice|28|47000|NYC|
|Charles|42|72000|LA|
|Debbie|45|71000|NYC|
|Emily|55|82000|LA|
|Frankie|23|37000|NYC|
|George|52|43000|LA|
|Hillary|48|48000|NYC|
|Irene|31|42000|LA|
|Jeffrey|27|39000|NYC|
|Kevin|21|27000|LA|

Create a class `Employee` so that its objects will hold this data. Add the objects to a map that maps the name of an employee to the `Employee` object holding this employees data.

Then, using stream processing, compute the following statistics and results and print them out:

1. Overall average age.
2. Average salary of employees over 30 years in the `NYC` office.
3. Names of all employees older than fourty with a salary below 50.000.
4. Number of employees per office.
