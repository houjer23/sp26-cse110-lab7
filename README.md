# From Jerry Hou

## Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.

Within a Github action that runs whenever code is pushed

This is best because automated end-to-end tests should catch bugs as soon as new code is added to the project. Running them through GitHub Actions makes the testing process automatic so that developers do not have to run them manually, preventing not working codes to be merged to main. Developers might forget to run the test manually if the Github action is not setup.

## Would you use an end to end test to check if a function is returning the correct output?

No

## What is the difference between navigation and snapshot mode?

Navigation mode evaluates the page right after it loads and gives an overall performance score, but it does not analyze later interactions or content changes. Snapshot mode evaluates the page in its current state and is best for finding accessibility issues, but it cannot measure JavaScript performance.

## Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.

1. Add a lang attribute to the html tag so screen readers can correctly identify the page language.
2. Add a meta description so search engines can better summarize and display the page in search results.
3. Optimize the mobile viewport/tap interactions so mobile users do not experience delayed tap responses.