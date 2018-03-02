# Feed Reader Testing
This is the last project of Udacity's Front-End Developer nanodegree. In this project, we are given a web-based application that reads RSS feeds, and we should apply test suites using [Jasmine](http://jasmine.github.io/).


## How to launch
Simply clone/download this repository to your local client then double click to index.html to launch the app. You can also run a [local server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server) for a bonus.

## Tasks
1. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
2. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
3. Write a new test suite named `"The menu"`.
4. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
5. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
6. Write a test suite named `"Initial Entries"`.
7. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
8. Write a test suite named `"New Feed Selection"`.
9. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
10. No test should be dependent on the results of another.
11. Callbacks should be used to ensure that feeds are loaded before they are tested.
12. Implement error handling for undefined variables and out-of-bound array access.
13. When complete - all of your tests should pass. 
14. Write a README file detailing all steps required to successfully run the application. If you have added additional tests (for Udacious Test Coverage), provide documentation for what these future features are and what the tests are checking for.
