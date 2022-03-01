print("All in one")
ch=int(input("1. Even Odd\n2. Greatest Num\n3. Square Cube\n4. Addition\n"))
if ch==1:
    val=int(input("Enter value"))
    if val%2==0:
        print("No is even",val)
    else:
        print("Num is odd",val)
elif ch==2:
    print("Find gretest numnber")
    num1=int(input("Enter first value"))
    num2=int(input("Enter Second value"))
    num3=int(input("Enter third value"))
    if num1>num2 and num1>num3:
        print("Greatest value is:",num1)
    elif num2>num1 and num2>num3:
        print("Greatest value is:",num2)
    else:
        print("Greatest value is:",num3)
elif ch==3:
    num7=int(input("Enter any value"))
    print("Square of num is :",num7*num7)
    print("Cube of num is :",num7*num7*num7)
elif ch==4:
    num1=int(input("Enter first value"))
    num2=int(input("Enter Second value"))
    print("Addition is:",num1+num2)
else:
    print("****Invalid Input*****")
