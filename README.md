# codsoft-project-2
def calculator():
  print("Calculator")
  print("Operation to be performed:")
  print("1. Addition")
  print("2. Subtraction")
  print("3. Multiplication")
  print("4. Division")
  try:
    a=int(input("Enter the First number: "))
    b=int(input("Enter the Second number: "))
    choice = int(input("Enter your Choice: "))
    if choice == 1:
      print(a+b)
    elif choice == 2:
      print(a-b)
    elif choice == 3:
      print(a*b)
    elif choice == 4:
      if b!=0:
        print(a/b)
      else:
        print("Error:Infinity")
    else:
      print("Invalid choice")
  except:
    print("Invalid input")
calculator()
