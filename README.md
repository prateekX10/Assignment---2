# ASSIGNMENT - 2
# TASK - 1


num = int(input("Enter a Number: "))
if num % 2 != 0:
  print(str(num) + " is an Odd Number")
else:
  print(str(num) + " is an Even Number")

#TASK - 2

total = 0
for i in range(1, 50):
  total += i
print("The sum of integers from 1 to 50 is " + str(total))
