CSCI 103 Programming Assignment 1, Hailstone, Spring 2015

Name:Sandeep Suresh

Email Address: sureshsa@usc.edu

NOTE: You can delete the questions, we only need your responses.

NOTE: It is helpful if you write at most 80 characters per line,
and avoid including special characters, so we can read your responses.

Please summarize the help you found useful for this assignment, which
may include office hours, discussion with peers, tutors, et cetera.
Saying "a CP on Tuesday" is ok if you don't remember their name.
If none, say "none".

:

================================ Questions ==================================

1. Which kind of a loop did you use for the first program? Why?

:

2a. Once you've completed the second program, run hailstats on the following
inputs, and record your results in the table below:

  input range  | minimum length | achieved by | maximum length | achieved by
-----------------------------------------------------------------------------
    50 100     |6               |64           |118             |97             
   100 200     |7               |128          |124             |171            
   200 400     |8               |256          |143             |327           

2b. What pattern do you think there is in the values achieving minimum length?
Can you explain why it holds?

:The pattern in achieving minimum length is they are all achieved by powers
of 2. This holds because when the number starts off even and a power of 2,
it will keep dividing by 2 until it reaches one. It will never reach an 
odd number that is not one, requiring the program to multiply by three and
add one.Thus, powers of 2 have the most streamlined path towards one.

3a. Let X be the smallest integer whose length is greater than 150.
By running your hailstats program several times on carefully chosen inputs,
determine what is the value of X.

X is :703

3b. Explain, briefly, the way in which you used your hailstats program
(i.e., which inputs you gave it) to find this answer.

:I decided to put a clause in my for loop that said, when the length of
the number put through the hailstone algorithm is greater than 150, print
out something declaring so. Once this was implemented, I searched a large
range (1-500) to see if anything came. Nothing did. So I went from 500 to
750 and got a hit with the number 703. I knew this had to be it because I
only got one statement that said there was a number with a length higher
than 150.

================================ Remarks ====================================

Filling in anything here is OPTIONAL.

Approximately how long did you spend on this assignment?

:2 Hours

Were there any specific problems you encountered? This is especially useful to
know if you turned it in incomplete.

:Not really! Logic at first was confusing. 

Do you have any other remarks?

:Cool project!
