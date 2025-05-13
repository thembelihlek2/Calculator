# Calculator
PLP Academy
 num1 = float(input("Enter the first number: "))
        num2 = float(input("Enter the second number: "))

        result = num1 + num2

        print(f"{num1} + {num2} = {result}")

    except ValueError:
        print("Error: Invalid input. Please enter a number.")

if _name_ == "_main_":
    calculator()
    
