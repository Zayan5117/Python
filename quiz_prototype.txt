#quiz score starts at 0
points = 0

#Question 1
answer = ("3.1415")
question = input("What are the first 5 digits of pi?: ")
question = question.strip().lower()
if question == answer:
    print("Correct")
    points += 1
else:
    print("Incorrect")
print("points: {}/5".format(points))

#Question 2
answer = ("4090")
question = input("What is the current best nvidia gpu model called(just number)?: ")
question = question.strip().lower()
if question == answer:
    print("Correct")
    points += 1
else:
    print("Incorrect")
print("points: {}/5".format(points))

#Question 3
answer = ("imagine dragons")
question = input("Who wrote the song Believer?: ")
question = question.strip().lower()
if question == answer:
    print("Correct")
    points += 1
else:
    print("Incorrect")
print("points: {}/5".format(points))

#Question 4
answer = ("amd")
answer2 = ("intel")
question = input("Name one of the 2 cpu manufacturers?: ")
question = question.strip().lower()
if question == answer:
    print("Correct")
    points += 1
elif question == answer2:
    print("Correct")
    points += 1
else:
    print("Incorrect")
print("points: {}/5".format(points))

#Question 5
answer = ("windows")
answer2 = ("windows 10")
question = input("What operating system do these computers use?: ")
question = question.strip().lower()
if question == answer:
    print("Correct")
    points += 1
elif question == answer2:
    print("Correct")
    points += 1
else:
    print("Incorrect")
print("points: {}/5".format(points))

#Some of the functions used and how they are used:

#the .strip() function removes all spaces from the inputted text
#the .lower() function converts all letters from the inputted text to lower case
# == means equal to
#input() allows you to input text to be used by the code

