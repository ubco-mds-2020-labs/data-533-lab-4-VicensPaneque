# DATA 533: Collaborative Software Development

# Assignment 4

## Objective
1.	Understanding how to set-up continuous integration using Travis 
2.	Understanding how to write code to handle errors and exceptions 

## Overall goal
In this lab, you will work collaboratively in the same group that you formed in lab 2. This time, you will set-up continuous integration using Travis. 

You will work on the same modules and methods that you develop in your lab 3, however, will add more codes that handle errors and exceptions gracefully.

You must ensure that the test suite for each function provides maximum coverage. Please include documentation (e.g., screenshots of [coverage.py](https://coverage.readthedocs.io/en/v4.5.x/) report) that shows you’ve checked for maximum coverage.

Continuous integration testing is set-up using Travis and the package README contains a status image showing the [status of your build](https://docs.travis-ci.com/user/status-images/#travis-ci-pages-show-the-default-branchs-result).

## Specific Expectations (20 marks)
- [6 marks] You must need to configure continuous integration testing using Travis-CI.
    - You can create a new GitHub repository and store your lab 3 code there. Add the other group member as a collaborator to the repository.
    - Clone the repository to your local machine. Create a new branch and write new code there.
    - Ask your group member to clone the GitHub repository, start writing code in a new branch.
    - Frequently push your updated code (i.e., the local repositories - at least once a day) to the GitHub repository.
    - You must need to configure continuous integration testing to handle the builds automatically
    - Create pull requests and merge your code into the master branch.
- [6 marks] At least six methods will contain appropriate error and exception handlers (out of six exceptions, two exceptions should be user-defined exceptions).
- [4 marks] You must ensure that the test suite for each function provides maximum coverage.
    - At least four methods should have ~100% coverage. Provide screenshots showing the coverage reports
- [1 mark] Your package README should contain a passing build stamp (see Resources).
- [2 marks] Have a Git history to demonstrates that the group members contributed equally.
- [1 mark] Publish the package (i.e., upload the package to PyPi) and add the link to the README file.

## Submission instructions: 

Please submit your GitHub or GitHub classroom link to Canvas (one submission from a group is good enough)


## Resources
- [Create CI Infrastructure Using Python, GitHub, and Travis CI](https://microsoft.github.io/PartsUnlimitedMRP/pandp/200.1x-PandP-PythonCI.html)
- [Embedding Status Images](https://docs.travis-ci.com/user/status-images/)