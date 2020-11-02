# basic_calculation
# To convert weight from either kilograms or pound
weight = int(input('Weight= '))
unit = input('(L)bs or (K)g :')
if unit.upper() == 'L':
    converted = weight / 2.2
    print(f"You are {converted} kilos")
if unit.upper() == 'K':
    converted = weight * 2.2
    print(f"You are {converted} pounds")

# Square a number
numb = int(input('Enter a number: '))
numbSquared = numb ** 2
print(f"The square of {numb} is {numbSquared}")

# temperature in celsius or farenheit
temp = int(input("What's your tempearture today? "))
unit = input('(C)elsius or (F)arenheit :')
if unit.upper() == 'C':
    converted = (temp * 1.8) + 32
    print(f"You are {converted} °F")
if unit.upper() == 'F':
    converted = (temp - 32) * 0.56
    print(f"You are {converted} °C")

# Arithmetic

number = (512 - 282) / (47.48 + 5)
print(number)
number = int(512 - 282) / int(47.48 + 5)
print(number)
number = float(512 - 282) / float(47.48 + 5)
print(number)

#Calculating Total bill

bill = float(input("How much is your bill: $"))
tip = float(bill * 0.2)
totalBill = bill + tip
print(f"Your total bill is ${totalBill}")
