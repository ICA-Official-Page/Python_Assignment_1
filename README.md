#Task 1

Takes two inputs from the user

input() function reads input as a string.

int() converts that string into an integer.

So, a and b become integers entered by the user.

Example:

Enter First Number: 10
Enter Second Number: 5


Performs four arithmetic operations

Addition: a + b → adds the two numbers.

Subtraction: a - b → subtracts second number from first.

Multiplication: a * b → multiplies the numbers.

Division: a / b → divides first number by second. (Result is a float in Python.)

Displays results with print()

Output for the above example:

Your Addition is 15

#Tsk 2
Takes first name as input

a = str(input("Enter the first Name: "))


input() asks the user to type something.

str() converts it into a string (though input() already returns string, so str() is optional).

The entered text is stored in variable a.

Example:

Enter the first Name: Kanhaiya


Takes last name as input

b = str(input("Enter the last Name: "))


Again takes input from user.

Stores it in variable b.

Example:

Enter the last Name: Sharma


Displays a greeting message

print("Hello " + a + " " + b + "! Welcome to the Python program.")


Concatenates (joins) the string "Hello " with the user’s first name, a space " ", the last name, and the welcome message.

Produces a full sentence.

Example Output:

Hello Kanhaiya Sharma! Welcome to the Python program.

Your Subtraction is 5
Your Multiplication is 50
Your Division is 2.0
