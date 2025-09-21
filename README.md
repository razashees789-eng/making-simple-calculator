a = int(input("enter the first number :"))
b = int(input("enter the second number :"))
op = input("enter the operator(+, -, *, /):")
if op == '+':
    print(a + b)
elif op == '-':
    print(a - b)
elif op =='*':
    print(a * b)
elif op == '/':
    print("error! divison by zero." if b == 0 else a / b)
else:
    print("invalid operator")
