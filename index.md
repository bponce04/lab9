# CSE 15L: Putting Everything Together

## Intro:

In this final lab-report, I will be going over a scenario involving a bug in a Student's code and I will show them what they got wrong and how I fixed it.

## Part 1: The Scenario

A CSE 15L is trying to run some JUnit tests to check out if their code in their lab3 directory is working as intended. The problem, however, is that their tests are not running because JUnit cannot find one particular item, `ArrayTests.java`.
Unsure what to do, the student decides to make a post on Edstem in regards to his problem:

![edstem](https://github.com/bponce04/lab9/blob/main/Edstem%20Mock-Up.png?raw=true)

This is what the Student's terminal looks like when trying to run the commands:

![terminal](https://github.com/bponce04/lab9/blob/main/Screenshot%202023-06-05%20at%2012.19.56%20PM.png?raw=true)

Later in the day, a TA takes a look at the Student's post and begins to review the commands that are causing the errors. The TA then discovers that the Student is using the right command except that in the second command, only the name of the java file should be provided, not the `.java` label at the end.

The TA responds to the Students post informing them of the correct way of running the JUnit commands:

>"Hi!
> It looks like It looks like you were trying to run these JUnit commands with the filename of the java AND the `.java` tag right after. 
> When you run the first command, it will already be searching for files that end with the tag. Running the second command will cause for it to crash, which is why it can't find `ArrayTests.java`. The command will be searching for the filename `ArrayTests`, not `ArrayTests.java`

After the Student recieves this message, they are not only relieved that the error was not caused by any other files in lab3, but they understand why they should only provide the name of the file (excluding the file type tag in the end).

Once the Student knows what to fix, they go back into the terminal and run the commands with the new revisions. Resulting in the tests to pass:

![correct](https://github.com/bponce04/lab9/blob/main/Screenshot%202023-06-05%20at%2012.31.48%20PM.png?raw=true)

## Part 2: End of the Quarter Reflection

One important thing I learned from the latter part of the quarter was redirecting outputs into a file. I find this skill interesting because it is convenient to keep a reference of what a particular output would look like (and how to exploit or prevent it).

Another importnat thing that I learned was being able to run bash scripts, I find it interesting that we are able to store a set amount of comands into a file, which makes it easier to perform them without having to typing (or tabbing) them out on a terminal manually.

Overall, it has been a pleasure of being in the class and I am greatly appreciative of all the important lessons on using a terminal.








