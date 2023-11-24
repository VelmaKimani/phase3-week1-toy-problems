# # Phase 3 Week 1(Toy Problems)

## Prerequisite
1. Create a repository on your GitHub account.

2. Use Python to wire down the solution.

3. Push the solution to the above repository once done.

4. Submit the repository link for grading

5. Ensure your repository has a well written README.

## Challenge 1: Converting 12-hour time to 24-hour time
Converting a 12-hour time like "8:30 am" or "8:30 pm" to 24-hour time (like "0830" or "2030") sounds easy enough, right? Well, let's see if you can do it!

You will have to define a function, which will be given an hour (always in the range of 1 to 12, inclusive), a minute (always in the range of 0 to 59, inclusive), and a period (either "am" or "pm") as input.

Your task is to return a four-digit string that encodes that time in 24-hour time.

## Challenge 2: Two numbers are positive.
Write a function which takes three integers a, b, and c as arguments, and returns True if exactly two of of the three integers are positive numbers (greater than zero), and False - otherwise.

### Examples:

_(2, 4, -3) == True_

_(-4, 6, 8) == True_

_(4, -6, 9) == True_

_(-4, 6, 0) == False_

_(4, 6, 10) == False_

_(-14, -3, -4) == False_

## Challenge 3: Consonant value

Given a lowercase string that has alphabetic characters only and no spaces, return the highest value of consonant substrings. Consonants are any letters of the alphabet except "aeiou".We shall assign the following values: a = 1, b = 2, c = 3, .... z = 26.

### Examples;

For the word "zodiacs", solve("zodiacs") = 26

_For example, for the word "zodiacs", let's cross out the vowels. We get: "z d cs"_

_-- The consonant substrings are: "z", "d" and "cs" and the values are z = 26, d = 4 and cs = 3 + 19 = 22. The highest is 26._

For the word "strength", solve("strength") = 57.

_The consonant substrings are: "str" and "ngth" with values "str" = 19 + 20 + 18 = 57 and "ngth" = 14 + 7 + 20 + 8 = 49. The highest is 57._

## Running the code
Press the run button in VSCode IDE

## Licence
 This project is Licensed under MIT. 