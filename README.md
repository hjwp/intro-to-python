# Intro to Python
A series of workshops for MADE employees to automate everyday computer tasks using the online, free course 'Automate The 
Boring Stuff' (https://automatetheboringstuff.com/) by Al Sweigart.

The workshops are split into the first 3 lessons being for Beginners - colleagues with no or minimal previous Python or 
programming experience, who would like to get their head around the foundation of programming with Python. Then there 
are 2 lessons for Intermediate level programmers - people who know the basics of Python or other programming languages
and would like to learn about web scraping and spreadsheet manipulation with Python.

You'll find that all of the 'Automate The Boring Stuff' chapters referred to in this course include a corresponding
YouTube video that contain the same content as the text, so feel free to use whichever works best for you.

## Lesson 0 - The Foundations of Python
"Lesson 0?" I hear you ask yourself. Why start counting from zero? The answer to this question will help you to 
understand some important fundamentals of programming and Python, and an in-depth answer will be found in `Lesson 2 - 
Data Structures` when we talk about `lists`. 

But here's the short-ish answer; computer programming is all about efficiency, and the reason for this set of 
workshops - to help colleagues learn Python, and hopefully, make efficiencies within their jobs for the benefit of 
themselves and MADE (an inspiring read on this topic can be found on 
https://www.wired.com/story/coders-efficiency-is-beautiful). So, with efficiency in mind, when looking at a list of 
colours `["red", "blue, "green", "yellow"]` at what position would you say is the colour `red`? You'd assume the answer 
would be `1` right? Well in programming and Python terms, that wouldn't be correct. The colour `red` is actually in 
position `0`. That is because when looking at the list, we will start in its first position, and do not have to move to 
find `red`. If this doesn't make sense right away, I hope it will after `Lesson 2`.

The first 2 chapters of 'Automate The Boring Stuff' discuss how to setup Python on your computer, and the basics of the
language. Please read through these chapters, setup Python if you don't have it already and try out all of the examples
in your Python console or IDLE.

[Chapter 0](https://automatetheboringstuff.com/chapter0/) - An introduction to setting up your computer with Python and 
the software required

[Chapter 1](https://automatetheboringstuff.com/chapter1/) - The basics of the Python programming language (expressions, 
integers, strings and variables)

## Lesson 1 - Controlling Code
Knowing how to read the flow of code, and control it yourself, is vital in programming. Some computer programs can be 
read top to bottom, others are distributed between multiple files and groups of code lines. This lesson should help you
in starting to understand these concepts and techniques.

Again, read through the 2 chapters below and try out the examples. If you come across errors, double check the code you
have written, as someone else to check it looks correct or break the problem down line by line, to ensure everything you
think is working, is. 

[Chapter 2](https://automatetheboringstuff.com/chapter2/) - Controlling the flow of programs (booleans, comparison 
operators, conditions, if statements, while loops, for loops, importing modules)

[Chapter 3](https://automatetheboringstuff.com/chapter3/) - What are functions, global and local scope and exception 
handling 

## Lesson 2 - Data Structures
Lesson #2! You're half way through the Beginner level lessons for this course, well done!! Today we will be looking at
what programmers call "data structures" which is a posh way of saying "data grouped together in a particular way". 

This will include `lists` which are values that contains other values in a particular order, such as a list of integers 
i.e. `[1, 3, 5, 7]`. We also have `tuples` which are similar to lists, but their subtle differences will be explained.
Last but not least, dictionaries, again a collection of values but with more useful ways of identifying data within them
using "keys". Read on dear colleague, and all will be revealed...

[Chapter 4](https://automatetheboringstuff.com/chapter4/) - The list and tuple data types and methods

[Chapter 5](https://automatetheboringstuff.com/chapter5/) - The dictionary data type and structuring data with them

## Lesson 3 - Strings
In programming we refer to text values as "strings", this is because in dawn of programming, this term was used to
describe a series of numbers or words, a "string of 1s". Moving on, text is extremely useful as input and output in
computer programs, so let's see how Python can let us play with strings.

[Chapter 6](https://automatetheboringstuff.com/chapter6/) - Working with strings and useful string methods

[Chapter 7](https://automatetheboringstuff.com/chapter7/) - Searching strings for patterns using regular expressions

## Lesson 3.5 - Warm Up
This lesson is intended for any Intermediate level programmers who have skipped the Beginner course, but would like to 
brush up on their basic Python skills (if you have just completed the Beginner course, please feel free to go through
any areas you found difficult, or skipping ahead to `Lesson 4`). 

I would recommend skimming through the first 6 chapters 'Automate The Boring Stuff' and answering the questions at the 
end of the chapters. 

[Chapter 0](https://automatetheboringstuff.com/chapter0/) - An introduction to setting up your computer with Python and 
the software required

[Chapter 1](https://automatetheboringstuff.com/chapter1/) - The basics of the Python programming language (expressions, 
integers, strings and variables)

[Chapter 2](https://automatetheboringstuff.com/chapter2/) - Controlling the flow of programs (booleans, comparison 
operators, conditions, if statements, while loops, 
for loops, importing modules)

[Chapter 3](https://automatetheboringstuff.com/chapter3/) - What are functions, global and local scope and exception 
handling 

[Chapter 4](https://automatetheboringstuff.com/chapter4/) - The list and tuple data types and methods

[Chapter 5](https://automatetheboringstuff.com/chapter5/) - The dictionary data type and structuring data with them

[Chapter 6](https://automatetheboringstuff.com/chapter6/) - Working with strings and useful string methods

The next 4 chapters are extremely useful to get the most out of these workshops, but that's a lot of reading, so they're
not mandatory.

[Chapter 7](https://automatetheboringstuff.com/chapter7/) - Searching strings for patterns using regular expressions

[Chapter 8](https://automatetheboringstuff.com/chapter8/) - Reading and writing files

[Chapter 9](https://automatetheboringstuff.com/chapter9/) - Copying, moving, renaming and compressing files

[Chapter 10](https://automatetheboringstuff.com/chapter10/) - Debugging your code and fixing issues 🐛

I would also heavily recommend reading [Appendix A](https://automatetheboringstuff.com/appendixa/) which explains 
installing third party modules - Python code that doesn't come as standard. This is done using the `pip` tool from the
command line i.e. running `pip install selenium` or `pip install requests`.

## Lesson 4 - Web Scraping
What the bloody hell is web scraping??? Do we take a shovel and start running it across our computer screens? Well 
obviously not, but it actually isn't that far from the analogy of shovelling data from a website into your own program.
Web scraping is the term used to describe a program that downloads data from a website, processes it and produces an 
output. That output could be a report of all the products that a competitor is selling for cheaper, or any updates to a
website since the program last ran.

Have a read of [Chapter 11](https://automatetheboringstuff.com/chapter11/) from Automate The Boring Stuff and Al will 
explain the `webbrowser` builtin module, opening web pages and downloading them, formatting web pages with `Beautiful 
Soup` and controlling websites using the `Selenium` Python module.

### Task 1 - Weather Report
Given a weather reporting website of your choice, write a Python script that will print out today's temperature.

**Top Tips:** 
- Breakdown the problem you have into small, manageable chunks that you understand. 
- Then do the same with the solution that you are trying to create. 
- Try not to get carried away with getting straight to the end result. 
- i.e. How do I download a webpage? Then once that's done, how do I convert that file into a Beautiful Soup object?

### Task 2 - I'm Feeling Lucky
Given a search term, write a Python script that will open the top 5 results from Bing in your web browser - I recommend
Bing because the HTML structure of Google results has become more complicated since Al wrote his course.

### Task 3 - Selenium
Now we get onto the fun stuff! Writing programs that can interact with webpages 😱. In this task, use what you have
learnt from Chapter 11 about Selenium to login to a social media account and post a message.

**Top Tips:**
- You'll need to download the `chromedriver` from https://chromedriver.chromium.org/downloads which will allow Python to
talk to your Chrome browser.
- Make sure the `chromedriver` version matches the version of your Chrome application.
- When creating the `browser` variable, pass as a parameter to the Chrome initialiser the location of your file i.e 
`browser = webdriver.Chrome(executable_path="/Users/smistry/Downloads/chromedriver")`

## Lesson 5 - Spreadsheet Manipulation
TBC
