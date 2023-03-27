# Simple-Calculator-project-in-Python
The application wasdesigned to accept user input for two numbers and an operation to perform. The result of the operation should then be displayed on the command line.
def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    return a / b

a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

print("Select operation:")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter choice (1/2/3/4): ")

if choice == '1':
    print(add(a, b))

elif choice == '2':
    print(subtract(a, b))

elif choice == '3':
    print(multiply(a, b))

elif choice == '4':
    print(divide(a, b))

else:
    print("Invalid choice")
