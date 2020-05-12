# Daily Coding Exercises

###  Day 1 - Printing to the Screen

Today will be focused on getting comfortable with printing.

First off you should have a Python IDE (Spyder) ready. Then you should enter the following into a file named  ```day1_python_exercises.py```



#### Simple Numbers & Math

Then **type (no copy/paste)** in the following code:

```Python
# Comment each line to predict the output before running the script.
print("I will now check some inventory:")
print("Bikes", 25 + 30 / 6)
print("Helmets", 100 - 25 * 3 % 4)

print "Now I will count the number of sales:"

# This math may seem wrong. Try exploring floating point numbers. Document the differences.
print 3 + 2 + 1 - 5 + 4 % 2 - 1 / 4 + 6

print("Is it true that 5 + 2 < 3 - 7?")

print(5 + 2 < 3 - 7)

print("What is 5 + 2?", 5 + 2)

print("What is 3 - 7?", 3 - 7)

print("Oh, that's why it's False")

print("Let's look at a few more.")

print("Is it greater than?", 5 > -2)
print("Is it greater than or equal?", 5 >= -2)
print("Is it less than or equal?", 5 <= -2)

# Explore the Differences
print("3" + 2)
print("3", 2)
print("3 + 2")
print("3" + "2")
print("3", "2")


# Notes:
# - % is the modulus operator. It calculates a remainder
# - There are multiple ways to print things. Using () is typically best practices for readability purposes
```



You should comment each line of code to describe what you think will be output. After running the program go back through each line, if your guess was incorrect make a note of why you were incorrect. This is a very simple and slow process, but it will help you understand the code better.



#### Formatting

Now you will practice some simple formatting. In the same file You should add a ```#%``` to create a new runnable block. This allows you to only run the code in the new block

Then enter the following code:

```python
string_a = "There are %d types of people." % 10
binary = "binary"
no_binary = "don't"
string_b = "Those who know %s and those who %s." % (binary, do_not)
string_c = "Those who know %s and those who %s." % binary, do_not

print(string_a)
print(string_b)
print(string_c)

# Using %r gives the raw data. Great for debugging.
print("What was that? %r" % string_a)
print("No the other part. '%s'" % string_b)

corny = True
joke_rating = "Was that joke horrible? %r"
print(joke_rating % corny)

left = "Left"
middle = "-"
right = "Right"
print(left + middle + right)

format_str = "Hi my name is {}!".format("Bob")
format_str = "Hi my name is {name}!".format(name="Bob")
format_str = "Hi my name is {name} and I am {age} years old looking for a job at {}".format(name=John, age=17, "Baylor")

names = ["Chris", "Ian", "Scott", "Bob"]
for name in names:
  print("Hi my name is {}".format(name))

people = {"Chris":22, "Ian": 19, "Scott": 23, "Bob": 12}
for person in people:
  print("Hi my name is {name} and I am {age} years old!".format(name=person, age=people[person])
```



This should give you a good understanding of simple output and formatting. There is much more you can do with formatting such as setting significant digits, padding aligning values to the left or right etc. You should explore all of these options as you have time. Python has a very good community with most of the answers to any questions you may have online.

