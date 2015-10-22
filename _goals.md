I'm going to learn **branches** workflow while I complete the practice problems. There's no real reason to use branches in this scenario -- I'm the only one working on the files -- but it's good practice.

*To Self:* When you're ready to work on a given quiz, you have a series of steps to follow. As an example, let's say you're ready to work on JavaScript Quiz 1. Here's our work through the terminal:
  1. **Make a Branch**. Create a new branch called js_quiz1_david. As a reminder, you do this using `git checkout -b js_quiz1_david`.
  2. **Copy and Rename** js_quiz1.md as js_quiz1_version_date. For example, if it's the first version and we're taking the quiz today, the command would be `cp js_quiz1 js_quiz1_v1_10-21`.
  3. **Take the Quiz**. Write your answers in the `js_quiz1_v1_10-21-2015` file. Save the file.
  4. **Grade Your Answers**. IF your answers are 100% correct -- not 90%, not 95%, but *all* correct -- then copy and rename your file as `js_quiz1_final.md`. In the terminal, the command would be cp js_quiz1_v1_10-21 js_quiz1_final. If you're not at 100% yet, that's okay for now. Move on to step 5. You must wait at least two days (but no greater than five days!) before trying the quiz again.
  5. **Add, Commit, Merge**. In your terminal, add the new file from your working directory to the staging area, then commit the changes to the head. Last, merge the changes with the master branch.
  6. **Delete the Branch** `git branch -d js_quiz1_david.`  

Follow this procedure for every quiz! Track your grades (as well as which problems you missed) in the *_progress.md* file.
