# Fizzbuzz
FizzBuzz is a popular coding challenge often used in coding interviews to assess the coding skills of candidates. The challenge requires printing the numbers from 1 to 100, but for multiples of three, "Fizz" is printed instead of the number, and for multiples of five, "Buzz" is printed. For numbers that are multiples of both three and five, "FizzBuzz" is printed.

In this project, I will write a Java program that solves the FizzBuzz challenge. The program will use a for loop to iterate through the numbers from 1 to 100 and use conditional statements to determine whether each number is a multiple of 3, 5, or both. The program will then print the appropriate output for each number.

To complete this project, I will utilize my knowledge of Java programming concepts, including loops, conditional statements, and arithmetic operators. I will also use good programming practices, such as proper indentation, variable naming conventions, and code commenting, to ensure that my code is clear and easy to read.

Program Overview:
```
public class FizzBuzz{
  
  public static void main(String[] args){
    for (int i = 1; i <= 100; i++){

      if (((i % 5) == 0) && ((i % 3) == 0)){
        System.out.println("Fizzbuzz");
      } else if ((i % 5) == 0){
        System.out.println("Buzz");
      } else if ((i % 3) == 0){
        System.out.println("Fizz");
      } else {
        System.out.println(i);
      }
     }
    }
  }
```
Expected Output:
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
... ... ...
Buzz
Fizz
82
83
Fizz
Buzz
86
Fizz
88
89
Fizzbuzz
91
92
Fizz
94
Buzz
Fizz
97
98
Fizz
Buzz
```
