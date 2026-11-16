print("-" * 35)
print("       PYTHON TUTORIAL")
print("-" * 35)

running = True
while running:

    print("\nWelcome, new user!")
    print("Do you want to learn Python?")
    print("1. YES")
    print("2. NO")

    start = int(input("Enter your choice: "))

    if start == 2:
        print("Thank you! Goodbye!")
        break

    elif start != 1:
        print("Invalid choice! Please enter 1 or 2.")
        break
       
    elif start == 1:
        print("yes")

    # ==========================================
    # LESSON MENU
    # ==========================================

    print("\n========== LESSON MENU ==========")
    print("1. Introduction to Programming")
    print("2. Basic Syntax")
    print("3. Arithmetic Operators")
    print("4. IF, ELIF, and ELSE")
    print("5. FOR LOOP")
    print("6. WHILE LOOP")

    lesson = input("Choose a lesson (1-6): ")

    # Each lesson starts with zero points.
    score = 0

    # ==========================================
    # LESSON 1: INTRODUCTION
    # ==========================================

    if lesson == "1":

        print("\n--- INTRODUCTION TO PROGRAMMING ---")
        print("Python is a programming language.")
        print("It gives instructions to a computer.")

        print("\nExample code:")
        print('print("Hello World!")')
        print("Output: Hello World!")

        print("\nCODING CHALLENGE")
        print("Which code displays Hello Python?")
        print('1. print("Hello Python")')
        print('2. input("Hello Python")')
        print("3. print(Hello Python)")

        answer = input("Your answer: ")

        if answer == "1":
            print("Correct! +10 points")
            print("Output: Hello Python")
            score += 10
        else:
            print('Incorrect! The answer is print("Hello Python")')

    # ==========================================
    # LESSON 2: BASIC SYNTAX
    # ==========================================

    elif lesson == "2":

        print("\n--- BASIC SYNTAX ---")
        print("print() displays text.")
        print("input() receives information.")
        print("# creates a comment.")
        print("Variables store information.")

        print("\nExample:")
        print('name = "Alex"')
        print("print(name)")
        print("Output: Alex")

        print("\nCODING CHALLENGE")
        print("What is the output of this code?")
        print('print("Welcome!")')
        print("1. print")
        print("2. Welcome!")
        print("3. Welcome")

        answer = input("Your answer: ")

        if answer == "2":
            print("Correct! +10 points")
            print("Output: Welcome!")
            score += 10
        else:
            print("Incorrect! The output is Welcome!")

    # ==========================================
    # LESSON 3: ARITHMETIC OPERATORS
    # ==========================================

    elif lesson == "3":

        print("\n--- ARITHMETIC OPERATORS ---")
        print("+ Addition")
        print("- Subtraction")
        print("* Multiplication")
        print("/ Division")
        print("// Floor division")
        print("% Modulo")
        print("** Exponentiation")

        print("\nExample:")
        print("print(10 + 5)")
        print("Output: 15")

        print("\nCODING CHALLENGE")
        print("Which operator is used for multiplication?")
        print("1. +")
        print("2. *")
        print("3. /")

        answer = input("Your answer: ")

        if answer == "2":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! The multiplication operator is *.")

        print("\nBONUS CHALLENGE")
        print("What is the output of print(8 * 2)?")
        print("1. 10")
        print("2. 16")
        print("3. 4")

        answer = input("Your answer: ")

        if answer == "2":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! 8 multiplied by 2 is 16.")

    # ==========================================
    # LESSON 4: IF, ELIF, AND ELSE
    # ==========================================

    elif lesson == "4":

        print("\n--- IF, ELIF, AND ELSE ---")
        print("if checks a condition.")
        print("elif checks another condition.")
        print("else handles the remaining cases.")

        print("\nExample code:")
        print("age = 16")
        print("if age >= 18:")
        print('    print("Adult")')
        print("else:")
        print('    print("Teenager")')

        print("\nOutput: Teenager")

        print("\nCODING CHALLENGE")
        print("Which keyword checks another condition?")
        print("1. if")
        print("2. elif")
        print("3. else")

        answer = input("Your answer: ")

        if answer == "2":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! The answer is elif.")

        print("\nBONUS CHALLENGE")
        print("What is the output?")
        print("score = 10")
        print("if score == 10:")
        print('    print("Correct")')
        print("1. Incorrect")
        print("2. Correct")
        print("3. Nothing")

        answer = input("Your answer: ")

        if answer == "2":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! The output is Correct.")

    # ==========================================
    # LESSON 5: FOR LOOP
    # ==========================================

    elif lesson == "5":

        print("\n--- FOR LOOP ---")
        print("A for loop repeats code over a sequence.")
        print("range(3) generates 0, 1, and 2.")

        print("\nExample code:")
        print("for i in range(3):")
        print('    print("Hello")')

        print("\nOutput:")
        print("Hello")
        print("Hello")
        print("Hello")

        print("\nCODING CHALLENGE")
        print("How many times does this loop repeat?")
        print("for i in range(5):")
        print("1. 4 times")
        print("2. 5 times")
        print("3. 6 times")

        answer = input("Your answer: ")

        if answer == "2":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! It repeats 5 times.")

        print("\nBONUS CHALLENGE")
        print("Which keyword starts a for loop?")
        print("1. for")
        print("2. repeat")
        print("3. loop")

        answer = input("Your answer: ")

        if answer == "1":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! The keyword is for.")

    # ==========================================
    # LESSON 6: WHILE LOOP
    # ==========================================

    elif lesson == "6":

        print("\n--- WHILE LOOP ---")
        print("A while loop repeats while a condition is true.")

        print("\nExample code:")
        print("count = 1")
        print("while count <= 3:")
        print("    print(count)")
        print("    count += 1")

        print("\nOutput:")
        print("1")
        print("2")
        print("3")

        print("\nCODING CHALLENGE")
        print("Which keyword starts a while loop?")
        print("1. if")
        print("2. for")
        print("3. while")

        answer = input("Your answer: ")

        if answer == "3":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! The keyword is while.")

        print("\nBONUS CHALLENGE")
        print("What does count += 1 do?")
        print("1. Adds 1 to count")
        print("2. Subtracts 1 from count")
        print("3. Sets count to zero")

        answer = input("Your answer: ")

        if answer == "1":
            print("Correct! +10 points")
            score += 10
        else:
            print("Incorrect! It adds 1 to count.")

    # ==========================================
    # INVALID LESSON
    # ==========================================

    else:
        print("Invalid lesson! Choose from 1 to 6.")
        continue

    # ==========================================
    # LESSON RESULTS
    # ==========================================

    print("\n========== LESSON RESULTS ==========")
    print("Your score:", score)

    if score == 20:
        print("Excellent! Perfect score!")
    elif score == 10:
        print("Good job! Keep practicing!")
    else:
        print("Keep learning! You can do better!")

    # ==========================================
    # LEARN ANOTHER LESSON
    # ==========================================

    print("\nDo you want to learn another lesson?")
    print("1. YES")
    print("2. NO")

    again = int(input("Enter your choice: "))

    if again == 1:
        print("Returning to the lesson menu...")
        

    elif again == 2:
        print("Thank you for learning Python!")
        print("Goodbye!")
        break

    elif again != 1:
        print("Invalid choice!.")
        break
