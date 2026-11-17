while True:
    print("\n========================================")
    print("          PYTHON TUTORIAL")
    print("========================================")
    print("[1] Variables")
    print("[2] Data Types")
    print("[3] Python Syntax")
    print("[4] Print Statement")
    print("[5] Print Text")
    print("[6] Printing Numbers")
    print("[7] Python Comments")
    print("[8] Variable Naming Rules")
    print("[9] Assigned Value to Variable")
    print("[10] Declaration of Variables")
    print("[11] Assign Value and Output the Value")
    print("[12] Arithmetic Operators")
    print("[13] Expression in Python")
    print("[14] Basic Input and Output in Python")
    print("[15] Converting Input to Other Data Types")
    print("[16] Conditional Statement in Python")
    print("[17] Nested Condition in Python")
    print("[18] Logical Operators")
    print("[19] Iteration")
    print("[20] Types of Loops in Python")
    print("[0] Exit Tutorial")
    print("========================================")

    choice = input("Enter your choice: ")

    if choice == "0":
        print("\nThank you for using Python Tutorial!")
        break

    elif choice == "1":
        print("\nLesson 1: VARIABLES")
        print("\nDEFINITION:")
        print("Variables are used to store data.")
        print("\nEXPLANATION:")
        print("A variable is a name that holds a value.")
        print("\nEXAMPLE:")
        print('name = "Prince"')
        print("age = 18")
        print("\nOUTPUT:")
        print("name = Prince")
        print("age = 18")

        example = '''name = "Prince"
age = 18
print(name)
print(age)'''

    elif choice == "2":
        print("\nLesson 2: DATA TYPES")
        print("\nDEFINITION:")
        print("Data types define the kind of data stored.")
        print("\nEXPLANATION:")
        print("Common data types are string, integer, float, and boolean.")
        print("\nEXAMPLE:")
        print('name = "Prince"')
        print("age = 18")
        print("height = 5.8")
        print("is_student = True")
        print("\nOUTPUT:")
        print("Prince")
        print("18")
        print("5.8")
        print("True")

        example = '''name = "Prince"
age = 18
height = 5.8
is_student = True

print(name)
print(age)
print(height)
print(is_student)'''

    elif choice == "3":
        print("\nLesson 3: PYTHON SYNTAX")
        print("\nDEFINITION:")
        print("Syntax refers to the rules of writing Python code.")
        print("\nEXPLANATION:")
        print("Python code must follow proper writing rules.")
        print("\nEXAMPLE:")
        print('print("Hello World")')
        print("\nOUTPUT:")
        print("Hello World")

        example = '''print("Hello World")'''

    elif choice == "4":
        print("\nLesson 4: PRINT STATEMENT")
        print("\nDEFINITION:")
        print("The print() statement displays output.")
        print("\nEXPLANATION:")
        print("It is used to show text, numbers, and values.")
        print("\nEXAMPLE:")
        print('print("Welcome to Python")')
        print("\nOUTPUT:")
        print("Welcome to Python")

        example = '''print("Welcome to Python")'''

    elif choice == "5":
        print("\nLesson 5: PRINT TEXT")
        print("\nDEFINITION:")
        print("Text in Python is written inside quotation marks.")
        print("\nEXPLANATION:")
        print("You can use single or double quotation marks.")
        print("\nEXAMPLE:")
        print('print("Hello")')
        print("print('Welcome')")
        print("\nOUTPUT:")
        print("Hello")
        print("Welcome")

        example = '''print("Hello")
print('Welcome')'''

    elif choice == "6":
        print("\nLesson 6: PRINTING NUMBERS")
        print("\nDEFINITION:")
        print("Numbers can be displayed using print().")
        print("\nEXPLANATION:")
        print("Numbers do not need quotation marks.")
        print("\nEXAMPLE:")
        print("print(100)")
        print("print(25.5)")
        print("\nOUTPUT:")
        print("100")
        print("25.5")

        example = '''print(100)
print(25.5)'''

    elif choice == "7":
        print("\nLesson 7: PYTHON COMMENTS")
        print("\nDEFINITION:")
        print("Comments are notes written inside Python code.")
        print("\nEXPLANATION:")
        print("Comments start with the # symbol.")
        print("Python ignores comments when running the code.")
        print("\nEXAMPLE:")
        print("# This is a comment")
        print('print("Hello World")')
        print("\nOUTPUT:")
        print("Hello World")

        example = '''# This is a comment
print("Hello World")'''
       
    elif choice == "8":
        print("\nLesson 8: VARIABLE NAMING RULES")
        print("\nDEFINITION:")
        print("Variable names identify stored values.")
        print("\nEXPLANATION:")
        print("Names cannot start with a number or contain spaces.")
        print("\nEXAMPLE:")
        print('student_name = "Prince"')
        print("age = 18")
        print("\nOUTPUT:")
        print("student_name = Prince")
        print("age = 18")

        example = '''student_name = "Prince"
        
age = 18
print("student_name =", student_name)
print("age =", age)'''

    elif choice == "9":
        print("\nLesson 9: ASSIGNED VALUE TO VARIABLE")
        print("\nDEFINITION:")
        print("A value can be assigned to a variable using the = sign.")
        print("\nEXPLANATION:")
        print("The equal sign assigns a value to a variable.")
        print("\nEXAMPLE:")
        print('name = "Prince"')
        print("age = 18")
        print("\nOUTPUT:")
        print("Prince")
        print("18")

        example = '''name = "Prince"
age = 18

print(name)
print(age)'''

    elif choice == "10":
        print("\nLesson 10: DECLARATION OF VARIABLES")
        print("\nDEFINITION:")
        print("A variable is created when you assign a value to it.")
        print("\nEXPLANATION:")
        print("Python does not require a separate variable declaration.")
        print("\nEXAMPLE:")
        print('name = "Prince"')
        print("age = 18")
        print("\nOUTPUT:")
        print("Prince")
        print("18")

        example = '''name = "Prince"
age = 18

print(name)
print(age)'''

    elif choice == "11":
        print("\nLesson 11: ASSIGN VALUE AND OUTPUT THE VALUE")
        print("\nDEFINITION:")
        print("You can assign a value and display it using print().")
        print("\nEXPLANATION:")
        print("First, store a value in a variable.")
        print("Then use print() to display the value.")
        print("\nEXAMPLE:")
        print('city = "Manila"')
        print("print(city)")
        print("\nOUTPUT:")
        print("Manila")

        example = '''city = "Manila"
print(city)'''

    elif choice == "12":
        print("\nLesson 12: ARITHMETIC OPERATORS")
        print("\nDEFINITION:")
        print("Arithmetic operators perform mathematical operations.")
        print("\nEXPLANATION:")
        print("The operators include +, -, , /, %, //, and *.")
        print("\nEXAMPLE:")
        print("print(10 + 5)")
        print("print(10 - 5)")
        print("print(10 * 5)")
        print("print(10 / 5)")
        print("\nOUTPUT:")
        print("15")
        print("5")
        print("50")
        print("2.0")

        example = '''print(10 + 5)
print(10 - 5)
print(10 * 5)
print(10 / 5)'''

    elif choice == "13":
        print("\nLesson 13: EXPRESSION IN PYTHON")
        print("\nDEFINITION:")
        print("An expression is a combination of values and operators.")
        print("\nEXPLANATION:")
        print("Expressions produce a result when evaluated.")
        print("\nEXAMPLE:")
        print("result = 10 + 5 * 2")
        print("print(result)")
        print("\nOUTPUT:")
        print("20")

        example = '''result = 10 + 5 * 2
print(result)'''

    elif choice == "14":
        print("\nLesson 14: BASIC INPUT AND OUTPUT IN PYTHON")
        print("\nDEFINITION:")
        print("Input receives data and output displays information.")
        print("\nEXPLANATION:")
        print("input() gets information from the user.")
        print("print() displays information.")
        print("\nEXAMPLE:")
        print('name = input("Enter your name: ")')
        print('print("Hello", name)')
        print("\nOUTPUT:")
        print("Enter your name: Prince")
        print("Hello Prince")

        example = '''name = input("Enter your name: ")
print("Hello", name)'''

    elif choice == "15":
        print("\nLesson 15: CONVERTING INPUT TO OTHER DATA TYPES")
        print("\nDEFINITION:")
        print("Input can be converted into other data types.")
        print("\nEXPLANATION:")
        print("int() converts input into an integer.")
        print("float() converts input into a decimal number.")
        print("str() converts a value into text.")
        print("\nEXAMPLE:")
        print('age = int(input("Enter your age: "))')
        print("print(age)")
        print("\nOUTPUT:")
        print("Enter your age: 18")
        print("18")

        example = '''age = int(input("Enter your age: "))
print(age)'''

    elif choice == "16":
        print("\nLesson 16: CONDITIONAL STATEMENT IN PYTHON")
        print("\nDEFINITION:")
        print("Conditional statements make decisions in a program.")
        print("\nEXPLANATION:")
        print("Python uses if, elif, and else.")
        print("\nEXAMPLE:")
        print("age = 18")
        print("if age >= 18:")
        print('    print("You are an adult")')
        print("else:")
        print('    print("You are a minor")')
        print("\nOUTPUT:")
        print("You are an adult")

        example = '''age = 18

if age >= 18:
    print("You are an adult")
else:
    print("You are a minor")'''

    elif choice == "17":
        print("\nLesson 17: NESTED CONDITION IN PYTHON")
        print("\nDEFINITION:")
        print("A nested condition is an if statement inside another if statement.")
        print("\nEXPLANATION:")
        print("It allows a program to check multiple conditions.")
        print("\nEXAMPLE:")
        print("age = 18")
        print("has_id = True")
        print("if age >= 18:")
        print("    if has_id:")
        print('        print("You can enter")')
        print("    else:")
        print('        print("ID required")')
        print("else:")
        print('    print("You are too young")')
        print("\nOUTPUT:")
        print("You can enter")

        example = '''age = 18
has_id = True

if age >= 18:
    if has_id:
        print("You can enter")
    else:
        print("ID required")
else:
    print("You are too young")'''

    elif choice == "18":
        print("\nLesson 18: LOGICAL OPERATORS")
        print("\nDEFINITION:")
        print("Logical operators combine or reverse conditions.")
        print("\nEXPLANATION:")
        print("The three main operators are and, or, and not.")
        print("\nEXAMPLE:")
        print("print(True and True)")
        print("print(True or False)")
        print("print(not True)")
        print("\nOUTPUT:")
        print("True")
        print("True")
        print("False")

        example = '''print(True and True)
print(True or False)
print(not True)'''

    elif choice == "19":
        print("\nLesson 19: ITERATION")
        print("\nDEFINITION:")
        print("Iteration means repeating a set of instructions.")
        print("\nEXPLANATION:")
        print("Loops are used to repeat code multiple times.")
        print("\nEXAMPLE:")
        print("for i in range(3):")
        print("    print(i)")
        print("\nOUTPUT:")
        print("0")
        print("1")
        print("2")

        example = '''for i in range(3):
    print(i)'''

    elif choice == "20":
        print("\nLesson 20: TYPES OF LOOPS IN PYTHON")
        print("\nDEFINITION:")
        print("Python has two main types of loops: for and while.")
        print("\nEXPLANATION:")
        print("A for loop repeats over a sequence.")
        print("A while loop repeats while a condition is true.")
        print("\nEXAMPLE:")
        print("for i in range(3):")
        print('    print("Hello")')
        print("\nOUTPUT:")
        print("Hello")
        print("Hello")
        print("Hello")

        example = '''for i in range(3):
    print("Hello")'''

    else:
        print("\nInvalid choice! Please select from 1 to 20.")
        continue

    
    while True:
        print("\n========================================")
        print("[1] Try the Example")
        print("[2] Return to Main Menu")
        print("[0] Exit Tutorial")
        print("========================================")

        action = input("Enter your choice: ")

        if action == "1":
            print("\nTRY THE EXAMPLE")
            print("Copy this code and try it in OnlineGDB:")
            print("\n" + example)

            input("\nPress ENTER when you have finished...")
            break

        elif action == "2":
            break

        elif action == "0":
            print("\nThank you for using Python Tutorial!")
            break

        else:
            print("Invalid choice! Please select 1, 2, or 0.")
        if action == "0":
            break    



            


    if action == "0":
        break    
