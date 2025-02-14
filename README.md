# Mercator unit testing afternoon task!

This repo contains the unit testing task.

**Your task is to implement TDD to create an income tax calculator!**

Steps to follow:

**Cloning this repository**
1.	Start by copying the SSH link. Make sure SSH is underlined orange before you copy so you know you are getting the correct link.
2.	In your terminal, direct to the place you want to save the repository and run ‘git clone <SSH LINK>’. Replace <SSH LINK> with the copied link from step 1.
3.	You will now have a copy of the project which you can open in IntelliJ however the upstream will still point to the master copy. You can check this by running ‘git remote get-url origin’
4.	We need to change this. Start by making a new GitHub repository.
5.	Direct yourself to the repository in terminal, then run the following, substituting with your GitHub username and newly created repository name:

    5.1.    ‘git remote rename origin upstream’
      (The old origin is now renamed to upstream)

    5.2.    ‘git remote add origin git@github.com:username/repo-name.git’ 
        (A new origin is added, substitute in your github info. e.g. git remote add origin git@github.com:AprilGar/UnitTestingAfternoonTask.git)

6. Check the remote is correct by running ‘git remote -v’ (If this isn’t pointing to you, try step 5 again, if it still isn’t, seek help from a peer or your trainer!)
7. Now that the upstream points to you, you must make sure you use the keyword ‘origin’ when pushing. The command will be ‘git push origin <branch name>’
8. Do a git status and commit anything that is currently untracked. Then make yourself a branch for the MVP.

----
**MVP**
1. Now you have an MVP branch, spend time having a look through the repository and see what you have been given.
2. Write failing tests around the placeholder methods created.
3. Run the tests, making sure they fail.
4. Write just enough code to make the tests pass.
5. Refactor the code to make it cleaner and more readable.
6. When you are happy with your code, tests are passing, create a pull request (PR) and merge into main.
7. In IntelliJ, checkout main, pull ‘origin main’. Remember, we never work on main, main is only for finished code!
8. Send your GitHub link to your trainer.

---
To run the tests, you can use the green play button in your Spec, or in terminal, run:
```
sbt test
```
----
**Extension:**
1. Once all your code is pulled down, branch off main for the extension.
2. Refactor the code with the corrected income tax bands, via: https://www.gov.uk/income-tax-rates
3. Extend the task to calculate capital gains from shares. Information on implementation can be found here https://www.gov.uk/capital-gains-tax/rates and https://taxscouts.com/the-tax-basics/capital-gains-tax-rates/
4. When you are happy with your code, tests are passing, create a PR and merge into main. In IntelliJ, checkout main, pull ‘origin main’.

---
**Hard Extension:**
1. Once all your code is pulled down, branch off main for the hard extension.
2. Extend the task to calculate total income tax AND capital gains tax from shares. Create a new method that calls your existing methods to accomplish this.
3. When you are happy with your code, tests are passing, create a PR and merge into main. In IntelliJ, checkout main, pull ‘origin main’.
