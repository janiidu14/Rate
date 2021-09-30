# Rate
Calculate the time taken to mow grass on a black.
#Prompt user for Area of House
while True:
    a = float(input("Widht of House in meters:"))
    if a > 0:
        break
while True:
    b = float(input("Lenght of House in meters:"))
    if b > 0:
        break

#Prompt user for Area of Block
while True:
    x = float(input("Width of Block in meters:"))
    if x > a:
        break
while True:
    y = float(input("Lenght of Block in meters:"))
    if y > b:
        break
    
#Rate
rate = str(((x*y) - (a*b))/2)
    
#Display Time
if rate == 1:
    print("Time taken to mow is " + rate + " minute")
else:
    print("Time taken to mow is " + rate + " minutes")
