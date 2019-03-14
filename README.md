
# Practical Data Cleaning - Lab


## Introduction
Now that you've been introduced to some of the basic approaches to cleaning up data, it's time for you to get some additional practice on your own. Remember, it's OK to look back at previous lessons and/or to use Google - professional programmers do both of those things all the time! And if you get stuck, feel free to ask a question - that's why we have an instructor in the classroom!

## Objectives
You will be able to:
* Perform simple data clean up operations on individual variables

## Getting Started
Remember that this is a "lab", so the first thing you need to do is download the code to work on it locally. Remember the flow?
* Click on the GitHub link in Learn on the lesson
* Click on the "Fork" button on GitHub to make your own fork (copy on GitHub)
* Open a Git Bash terminal window and type `git clone ` followed by the URL of your GitHub repository
* Type `cd ent-ds-del-1-4-practical-data-cleaning-lab` to "change directory" to the new one you just downloaded from GitHub
* Type `jupyter notebook` to start that running, and then click on the `index.ipynb` file that shows up in your browser.

## Changing Types

OK, lets start by doing the "math on strings" problem again. Fix the code in the next cell to give you the output you would expect . . .


```python
salary = "30000"
side_income = "2000"
total_income = salary + side_income
print(total_income)
```

## Booleans from Strings

Great, and now lets create a boolean for which town a person lives in (make sure your code handles different possible capitalizations):


```python
city = "AusTiN"
if city == "Austin":
    lives_in_austin = True
else:
    lives_in_austin = False
print(lives_in_austin)    
```

## Starting from Scratch

Up to this point, you've only had to modify code. Let's have you write some from scratch and get it working. In the next cell, create a variable called `state`. Set it to a value. Write code that (irrespective of capitalization) sets a variable `lives_in_arizona` to a boolean value of True or False based on the value of the state. Then add a line that prints out the boolean variable and make sure it works irrespective of the capitalization of the string within the `state` variable.

## Creating Booleans from Numbers

In the next cell, write some code that sets a variable (lets call it `taxes_paid`) to a string representation of a number - e.g. `taxes_paid = "12000"`.

Then add some code that will set a boolean `paid_lots_of_taxes` to True if tax paid was over \\$25k and sets it to False if it was equal or less than \\$25k.

## Working with Capitalization

In the next code cell, create a variable `company_name` with a value of "acMe cOmpanY"
The write code to output it as:
* All upper case
* All lower case
* With just the first letter of the first word capitalized
* With just the first letter of *every* word capitalized (hint: this is new, we haven't shown it to you. Google it - it's called "title case" and remember to include the key word "Python" in your Google search so you don't get the answer for how to do this in Ruby or Java which wouldn't be very helpful)

## Extra Credit

Allllrighty! We've covered the basics. If you're feeling a little overwhelmed and/or you're out of time, there is nothing wrong with stopping right here. 

In fact, let's take a moment to celebrate. A couple of hours ago you might not have really know what Jupyter Notebook, Python, variables and data types even were, and now you're using them all like a pro!

OK, now we're done with our happy dance, here are a couple of extra problems. As mentioned, they are not required if you're running out of time (or steam), but if you're looking for a little more challenge, they should allow you to practice both your coding and Googling skills!


### String Concatenation

In the code cell below, create three variables. `first_name`, `last_name` and `full_name`. Set the first and last names to your first and last names (or those of your favorite movie character) and write code to set the full name and display it based on first and last names. As always, think about capitalization to make sure that irrespective of the case for the first and last names, the full name looks good. 

### More Complex Conditionals

In the code cell below, create a variable called `city` and another called `lives_in_texas_major_metro`. Write some code so that if someone lives in Houston, Austin, or Dallas, `lives_in_texas_major_metro` is true. If they live anywhere else, it should be set to false. As always, make sure to consider capitalization!

## Summary

Great job - we're done with the "day 1" content. You've learned about variables and data types and how to clean up individual pieces of data. But usually you're not looking to clean up one name or address or date - you're looking to clean up a whole bunch of them.

So next up, we'll learn about some more complex data types in Python and how we can use them to store and iterate over collections of data.


