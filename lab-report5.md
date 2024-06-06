# Lab Report 5
## Part 1
## Question From Shaggy

Hello! I'm writing up my bash script for autograding the student submissions. I can see the bug has to do with a command not being found on line 27, but I'm still lost on which command might be the problem.

![Image](report5-1.png)

## Scooby's Answer

Notice you have have a conditional statement on line 27. I would suggest you review how conditionals are written in bash. They differ quite a bit from how they're written in Java, so I would pay close attention to not just syntax but also the format, including spacing.

## Output with Bug Fixed

![Image](report5-2.png)

The bug was merely a simple error in spacing within bash conditonals. Bash conditionals are written differently than Java conditionals in which everything is basically a terminal command. All instances of `$` in front of variables are seen as paths. Therefore, if they're not spaced, they'll be interpreted as a different command altogether, and an invalid one at that.

## Part 2

The second half of the quarter really introduced me to vim, which basically is a more direct way of accessing files within the terminal. Using various commands, one could not only open and read files within the terminal seconds after using the standard `cd` command as opposed to taking the time to open files on VSCode, but one also could edit them using commands such as the `i` insert command, alongside making a new file altogether.
