## Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed

This is best because automated end-to-end tests should catch bugs as soon as new code is added to the project. Running them through GitHub Actions makes the testing process automatic so that developers do not have to run them manually, preventing not working codes to be merged to main. Developers might forget to run the test manually if the Github action is not setup.

## Would you use an end to end test to check if a function is returning the correct output?

No