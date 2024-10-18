Q=float(input(“Enter the value of Discharge:”))

B1=float(input(“Enter the value of width at upstream: “))

B2= float(input(“Enter the value of width at downstream: “))

G=float(input(“Enter the value of acceleration due to Gravity:”))

Y1= float(input(“enter the value of upstream depth:”))

# Discharge per meter width

Q1=Q/B1

Q2=Q/B2

Print (“The value of discharge per meter width is:”, q1)

Print (“The value of discharge per meter width is:”, q2)

#Area Calculation

A1=B1*y1

Print(“The value of upstream area is: “, A1)

# Calculation of Froude Number

Fr1=((Q*Q*B1)/(g*A1*A1*A1))**0.5

Print( “The value of Froude number is:”, Fr1)

If(Fr1>1):

Print(“The flow is Super Critical Flow”)

Else:

Print(“The flow is Sub Critical Flow”)

# Upstream Energy

E1=y1+((Q*Q)/(2*g*A1*A1))

Print(“The value of at initial Section”, E1)

B2min=((27*Q*Q)/(8*g*E1*E1*E1))**0.5
