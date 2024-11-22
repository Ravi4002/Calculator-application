# Calculator-application
I have simple calculator application
print ("""""
    ***
+ ADD
- SUBTRACT
* MULTIPLY
/ DIVIDE
***
""")
num=int(input("enter the value:1"))
num=int(input("enter the value:2"))
opr=input("enter the opr..(+,-,/,*)")
if opr=="+":
    print(num+num)
elif opr=="-": 
       print(num-num)
elif opr=="*":       
    print(num*num)
elif  opr==" /":  
       print(num/num)
else:
    print("invalid operation...")
