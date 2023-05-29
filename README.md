# Lab 8 - Starter

1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed.

Automating our Continuous Integration and Continuous Delivery (CICD) pipeline is one of the most important things you can do as a part of Agile development. The easiest and most widely adopted solution requires the use of tools and GitHub actions is extremely convenient for our current workflow. We can improve the project's consistency, security, and workability by using Github actions at every stage, the goal of CI/CD.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no)

No, the use of end to end tests are to emulate the user's experience with the product/program. The goal of the unit test is the accomplish exactly what the question is asking so it's better to use that. End to end tests do not care if variables are working correctly but if functionality and user accomplishing their goals are more important.

3.  I might consider using a unit test to have a usability type test, but this is clearly more suited for a end to end test, as it directly impacts a feature of usability for the end user

4. This is the appropriate use for the unit test, as it checks an actual variable value we know to be false, the bread and butter behind the unit test.
