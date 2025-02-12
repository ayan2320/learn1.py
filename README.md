print("hello human")
def compare():
    x=int(input("whats x?"))
    y=int(input("whats y?"))
    if x>y:
        print("x is greater")
    elif y>x:
        print("y is greater")
    else:
        print("both are equal")
    if x>y or x<y:
        print("x is not equal to y")
    else:
        print("x and y are equal")
compare()
