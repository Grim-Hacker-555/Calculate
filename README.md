# Calculate

a = input ("number1 : ")
print ("**")
print ("*")
print ("/")
print ("+")
print ("-")
b = input ("    : ")
c = input ("number2 : ")
while True:
    if b == "**" :
        print (a**c)
    elif b == "*" :
        print (a*c)
    elif b == "/" :
        print (a/c)
    elif b == "+" :
        print (a+c)
    elif b == "-" :
        print (a-c)
    else :
        print ("error")
    a = a = input ("number1 : ")
    print ("**")
    print ("*")
    print ("/")
    print ("+")
    print ("-")
    b = b = input ("    : ")
    c = c = input ("number2 : ")
