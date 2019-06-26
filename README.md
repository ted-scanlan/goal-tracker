# goal-tracker #

## Daily notes and learning objectives for the next day. A way of gathering my thoughts, recapping what i've done for the day, and thinking about my objectives for tomorrow ##

### Mon 24th June ###



Goals for this week:

Makers academy GitHub - pills
Week outlines - goals
Work on “practicals” independently
Weekly challenges - pair in afternoons

“Technical learning resources”

SSL:
*  Track your learning - what I’ve learnt and goals for next day
*  GitHub repository
Trello
*   What to track : projects/ reflections / feedback
COPY SLACK MESSAGES - history gets deleted

Timetable for workshops on slack
Portfolio spreadsheet look at example


### Tuesday 25th June ###


#### Notes for the day: ####

**Debugging workshop:**

 * Bugs (at this stage) can be categorised in 2 seperate ways: the code itself (the code wont run) and the behaviour of the code (i.e. the code works but not in the desired way we want it to)


*  if you want to run only a unit test, i.e. just test a single method, run rspec spec./filename :linenumber

* cipher challenge
  * the error "nil can't be coerced into fixnum" normally means your entering nil into the procedure you are doing. in this case, your entering nil into the temporary parameter |char| that you're using to map out the chars of plaintext. so your telling the program to go and find char in a range (a...z) that doesnt contain it. If you look at the plaintext, it contains a Z, which isnt included in the range due to the (...)


  * ASCII NUMBERS
    * To us, a string such as "Hello world" looks like a series of letters with a space in the middle. To your computer, however, every String – in fact, everything – is a series of numbers. In our example, each character of the String "Hello world" is represented by a number between 0 and 127. For example, to the computer, the capital letter "H" is encoded as the number 72, whereas the space is encoded as the number 32. The ASCII standard, originally developed for sending telegraphs, specifies what number is used to represent each character.    65.chr #=> 'a'


#### Learning objectives for tomorrow: ####

* start on practical work in the morning - LEARN BY DOING

* develop further understanding of testing and Rspec syntax. Make sure i have a good debugging process. i.e. visibility ---- tightening the loop ---- knowing whats wrong before you try to fix it

* able to write tests from scratch of basic programs.

* finish the cipher challenge and understand how it works
