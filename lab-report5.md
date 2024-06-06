# Lab Report 4
## Question From Shaggy

Hello! I'm writing up my bash script for autograding the student submissions. I can see the bug has to do with a command not being found on line 27, but I'm still lost on which command might be the problem.

## Scooby's Answer

Notice you have have a conditional statement on line 27. I would suggest you review how conditionals are written in bash. They differ quite a bit from how they're written in Java, so I would pay close attention to not just syntax but also the format, including spacing.

## Output with Bug Fixed

The bug was merely a simple error in spacing within bash conditonals. Bash conditionals are written differently than Java conditionals in which everything is basically a terminal command. All instances of `$` in front of variables are seen as paths. Therefore, if they're not spaced, they'll be interpreted as a different command altogether, and an invalid one at that.
