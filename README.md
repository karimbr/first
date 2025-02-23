# first
print('hello this is my first repo')
# This program reads a sequence of numbers
# and counts how many numbers are even and how many are odd.
# The program terminates when zero is entered.

odd_numbers = 0
even_numbers = 0

try:
    number = int(input("Enter a number or type 0 to stop: "))
except:
    print('You have to enter a number')
    number = int(input("Enter a number or type 0 to stop: "))

while number != 0:
    
  if number % 2 == 0:
        even_numbers += 1
  else:
    odd_numbers += 1
    number = int(input("Enter a number or type 0 to stop: "))

print("Odd numbers count:", odd_numbers)
print("Even numbers count:", even_numbers)

