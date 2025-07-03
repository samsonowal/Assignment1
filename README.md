# Assignment1
# Python 3.13.5
Task 1: Perform Basic Mathematical Operations
Problem Statement: Write a Python program that does the following:
1.  Takes two numbers as input from the user.
2.  Performs the basic mathematical operations on these two numbers:
o	Addition
o	Subtraction
o	Multiplication
o	Division
3.  Displays the results of each operation on the screen.
4.  Input Collection:

          a = input('Enter the first number: ')
          b = input('Enter the second number: ')

    The program prompts the user to enter two numbers. These inputs are initially read as strings.

    Type Conversion:

          a = int(a)
          b = int(b)

    The input strings are converted into integers using the int() function, so arithmetic operations can be performed.

    Arithmetic Operations:
    
          add = a + b
          sub = a - b
          mul = a * b
          div = a / b

    The program performs:
     Addition and stores the result in add.
     Subtraction and stores the result in sub.
     Multiplication and stores the result in mul.
     Division (float division) and stores the result in div.

    Output Results:

          print('Addition= ', add)
          print('Subtraction= ', sub)
          print('Multiplication= ', mul)
          print('Division= ', div)

    Each result is printed on a new line with a label.


6.  Output:
7.  ![Screenshot 2025-07-03 121714](https://github.com/user-attachments/assets/408437c6-38e2-4c5e-a585-e860c118f9b4)





Task 2: Create a Personalized Greeting
Problem Statement: Write a Python program that:
1.  Takes a user's first name and last name as input.
2.  Concatenates the first name and last name into a full name.
3.  Prints a personalized greeting message using the full name.
4.  Input Collection:

              a = input('Enter Your First name: ')
              b = input('Enter Your Last name: ')

    The program prompts the user to enter their first name and stores it in variable a.

    Then, it asks for their last name and stores it in variable b.

    String Conversion (Redundant in This Case):

              a = str(a)
              b = str(b)

    This converts the input to strings, but since input() already returns strings by default, this step is unnecessary unless you expect other data types in future           versions.

    Output:

              print('Hello,', a, b + '! Welcome to the Python program.')

    The program prints a personalized greeting like:

    Hello, John Doe! Welcome to the Python program.
5.  Output:
6.  ![Screenshot 2025-07-03 122159](https://github.com/user-attachments/assets/9b2e55e2-4b93-4d9b-928d-c11078a4b3f0)
