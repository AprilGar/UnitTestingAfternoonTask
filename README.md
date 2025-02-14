# Mercator unit testing afternoon task!

This repo contains the unit testing task.

**Your task is to implement TDD to create an income tax calculator!**

Steps to follow:
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
**Extension task (1 - Hard):**
1. Once all your code is pulled down, branch off main for the extension.
2. Refactor the code with the corrected income tax bands, via: https://www.gov.uk/income-tax-rates
3. Extend the task to calculate capital gains from shares. Information on implementation can be found here https://www.gov.uk/capital-gains-tax/rates and https://taxscouts.com/the-tax-basics/capital-gains-tax-rates/
4. When you are happy with your code, tests are passing, create a PR and merge into main. In IntelliJ, checkout main, pull ‘origin main’.

---
**Extension task (2 - Really Hard):**
1. Once all your code is pulled down, branch off main for the hard extension.
2. Extend the task to calculate total income tax AND capital gains tax from shares. Create a new method that calls your existing methods to accomplish this.
3. When you are happy with your code, tests are passing, create a PR and merge into main. In IntelliJ, checkout main, pull ‘origin main’.
