# Midterm Exam Guide

## SI 506, Winter 2020

The midterm exam is open network, open readings, open notes, open slide decks. You may refer to
code in previous lecture exercises, lab exercises, and problem sets for inspiration.

Total exam time is approximately 75 minutes.

## 1.0 A few rules

:exclamation: Please arrive a few minutes early.  Make sure your personal laptop is fully charged.
Choose a seat with an empty seat on either side.

:warning: You are prohibited from soliciting assistance or accepting assistance from any person
while taking the exam. The midterm exam quiz and problem that you submit _must_ be your own work.

Likewise, you are prohibited from assisting any other student required to take this exam.  This
includes those taking the exam on Thursday, 27 February 2020, as well as those who may take the exam
at another time and/or place due to scheduling conflicts or other issues.

## 2.0 Two parts

The midterm exam consists of two parts: a quiz and a coding problem.

### 2.1 Quiz (500 points)

The quiz consists of __15 multiple choice questions__ drawn from the topics covered between week 03
and week 07:

* week 03: values, variables, expressions, statements, strings and lists, built-in functions
* week 04: function, conditional statement and operators, tracebacks, and docstrings
* week 05: for and while loops, control statements, list slicing, main() function, exceptions
* week 06: dictionaries, string slicing, exceptions
* week 07: tuples

Quiz questions are drawn from a number of question banks and are randomized for each student
attempt. The Canvas quiz engine will serve up one question per screen. You can navigate back and
forth between the previous and next questions while working on the quiz.

:warning: You are allowed a __single quiz attempt__. The quiz _must_ be completed before the
expiration of exam time (11:20 am) in order to earn points. Canvas will block submission if you 
attempt to submit the quiz after the  close of the midterm.

Once you submit the Canvas quiz for scoring please switch to working on the coding problem that you
will submit to Gradescope.

:bulb: Budget a maximum of 30 minutes (ideally less) for taking the quiz portion of the exam.

### 2.2 Coding Problem (500 points)

Two coding problems are provided.  Choose __one and only one__ to complete.

Both problems will be based on topics covered between week 03 and week 06. You will _not_ be asked
to write a `while` loop or work with tuples.

* week 03: values, variables, expressions, statements, strings and lists, built-in functions
* week 04: function, conditional statement and operators, tracebacks, and docstrings
* week 05: `for` loops, control statements, list slicing, `main()` function, exceptions
* week 06: dictionaries, string slicing, exceptions

You will download the problem files from Canvas Modules or Files. Review each problem quickly and
decide which problem you will work on.

Both problems involve replacing the placeholder `pass` statement with working code. You will
call the function from `main()` passing arguments to it per the instructions.

Each problem resembles the following skeletal implementation (verbose multi-line instructions are
reduced to a single line in the example):

```python
""" Multi-line general instructions. """

def some_function(some_parameter, maybe_another_parameter):
    """A description of some_function().

       Parameters:
            ...

        Returns:
            ...
    """

    pass # placeholder


def main():
    """Entry point for the program.

       Parameters:
            ...

        Returns:
            ...
    """

    # Add statements including calling some_function() per the directions.
    # Do something with the return value.

    pass



# Recall that a file executed from the command line is renamed to "main" by the
# Python Interpreter. Note too that functions must be called explicitly. Knowing
# this we can check the special built-in variable __name__ and, if the name
# equals "main", we can then call the main() function to commence the flow
# of execution.

if __name__ == '__main__':
    main()

```

## 3.0 Gradescope submissions

You may submit your problem solution to Gradescope as many times as needed before the expiration of
exam time. Your final submission will constitute your exam submission.

:warning: You _must_ submit your solution file to _Gradescope_ before the expiration of exam time.
Solution files submitted after the expiration of exam time will receive a zero score.

## 4.0 Auto grader / manual scoring

If the auto grader is unable to grade your submission successfully with a score of 500 points,
do not fear, we will grade your submission __manually__. Partial credit will be awarded for partial
submissions that otherwise fail the auto grader.

If you submit a partial solution, please include (if you have time) comments that explain what you
were attempting to accomplish in the area(s) of the function body that are not working properly. We
will review your comments when determining partial credit. Also, if your function fails to execute
properly, adding debug `print()` statements that show the parts that are working will also help us
in our review.

## 5.0 Exam tips

### 5.1 Browser setup

Consider opening a browser tab for each of the following resources _before_ commencing the exam:

| Browser tab | URL | Note |
| :---------- | :-- | :--- |
| Midterm Exam Guide | https://github.com/umsi-arwhyte/SI506-2019Winter/blob/master/docs/midterm/midterm_guide.md | Guide |
| Instructure Canvas | https://umich.instructure.com/courses/343044/ | See Canvas Modules for the link to the midterm Quiz and problems. |
| operators | https://www.w3schools.com/python/python_operators.asp | Operators reference |
| string methods | https://www.w3schools.com/python/python_ref_string.asp | String methods reference |
| list methods | https://www.w3schools.com/python/python_ref_list.asp | List method reference |
| dictionary methods | https://www.w3schools.com/python/python_ref_dictionary.asp | Dictionary method reference |

You may want to augment this minimal set up with tabs open to other resources. Don't over do it.
Too many tabs open could prove confusing.

### 5.2 Create a midterm directory
Create a directory named `midterm` on your laptop _before_ exam time. This is directory where you
will do your work. Make sure that directory is viewable in VS Code's explorer or other source
code or IDE directory/file viewer.

### 5.3 scratch.py

For the quiz consider creating a `scratch.py` file before exam time and place it in your
`midterm` directory. When answering individual quiz questions, you can use it to confirm your
answer by copying the code embedded in the quiz question into it. Correct the code as necessary, add
a `print()` statement, and run the file in VS Code or a __Bash shell__ and review the output.

:warning: Be wary of doing this for all questions; you may end up reducing the time you need to
complete the coding problem. The clock is not your friend.

### 5.4 Working on the problems

Download the two problems and put them in your `midterm` directory. Review each problem and then
choose one (and only one) to work on. Make frequent use of `print()` statements to print out values
as you are working on the problem. To test the file, run it in VS Code and/or the Bash shell and
confirm it is working before submitting it to Gradescope.

:exclamation: If you cannot get the problem working submit it to Gradescope anyways before the
expiration of exam time and we will grade it manually.

### 5.5 Run the Bash terminal

You can run your code in VS Code. You can also run your code in the terminal. Use `cd` to navigate
to your `midterm` directory and then run your files by invoking the Python Interpreter as in the
examples below:

Mac:

```cmd
$ python3 scratch.py
```

Windows:

```cmd
$ python scratch.py
```
