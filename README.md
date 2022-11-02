# Test Driven Development
# String Calculator

Create a simple String calculator with a method: int add(String numbers).

Think about the design first.

Write down a list of examples and discuss them with the group

Start with the simple features first

Clone the repository for an initial setup of your environment

# Feature 1
Provide two default delimiters for separating the numbers: , or \n

# Feature 2
Support additional delimiters in the following format

   “//[delimiter]\n[numbers...]”

# Feature 3
Calling add() with a negative number will throw an exception with the message “negative number are not allowed”. The exception should contain the negative number that was passed. If there are multiple negative numbers, list all of them in the exception message

# Feature 4
Numbers bigger than 1000 should be ignored, so adding 2 + 1001  = 2

# Feature 5
Delimiters can be of any length:
 “//[***]\n1***2***3” should return 6
