# Leap-Year-Calculator
#This code provides the basis for a simple leap year calculator in python
#look at the code in raw form and copy it into a python launcher
z = int(input("How many years would you like to calculate?"))
for a in range(z):
  year = int(input("Enter an year"))
  def leapyear(x):
    if x % 400 == 0:
      return True
    if x % 100 == 0:
      return False
    if x % 100 == 0:
      return True
    else:
      return False
    return x
  y = leapyear(year)
  print(y)
