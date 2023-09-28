# UOCIS322 - Project 0

Author: Evan Doster 

Contact: edoster@uoregon.edu

Description: This project aims to get you familiar with using git and modifying files. 

## Project 0 Instructions

### Files needed to be edited
- `Makefile`

### Instructions

- Copy `credentials-skel.ini` it to `credentials.ini` and fill in appropriately.

- Modify the program so that it prints "Hello
  world", nothing more and nothing less.  Note that you should do this ONLY by adding a single line to `Makefile`, and modifying `credentials.ini`.

- Replace these instructions with a proper README including the
   author, contact address, and a brief description of what the
   software does.

- Test, commit, push, test again, and turn in.
   - Use `make install` to set up.
   - Use `make run` to run.
   - Use `git status` to monitor changes
   - Use `git add $FILE` to stage files (new and existing). 
   		- **DO NOT ADD/PUSH `credentials.ini`!**
   - Use `git commit -m $MESSAGE` to commit staged changes (those `add`ed) with a commit message.
   - Use `git push` to push local commits.
   - To test, clone elsewhere (the server), and test (do `make install` and `make run`), it should work as expected.
   - Turn the project in by submitting your **filled in** `credentials.ini` file to Canvas.


## Grading Rubric

* If everything works as expected, 100 will be assigned.
* If the correct message is not shown ("Hello World"), 20 points will be docked.
* If `make run` fails, 20 points will be docked.
* If `make install` fails, 20 points will be docked.
* If `credentials.ini` is commited, 10 points will be docked.
* If `README.md` is not updated with your name and info, 10 points will be docked.
* If `credentials.ini` is incorrect or not submitted, 0 will be assigned.
