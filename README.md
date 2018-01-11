FEND - Feed RSS Reader Jasmine Testing Suites
===========================================

Given a web-based application that reads RSS feeds. How to use Jasmine to write a number of tests against a pre-existing application.

![Click on the image to see the demo in YouTube](https://img.youtube.com/vi/E5QiTgOLPKA/0.jpg)](https://www.youtube.com/watch?v=E5QiTgOLPKA)

## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What will I learn?

You will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How will this help my career?

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.

## Features

Libraries

- [Jasmine 2.1.2](http://jasmine.github.io/)
- [jQuery for DOM manipulation](http://jquery.com/)
- [Handlebars JS 2.0.0 to build semantic templates](http://handlebarsjs.com/)

Source Code

- The testing code is located in  /jasmine/spec/feedreader.js and written in Javascript ES6.
- The app is located in /js/app.js.

## Demo

If you want to play this project, click here: [Feedreader Jasmine Testing Suites Demo](https://claudiainbytes.github.io/feedreader-jasmine-testing)

## Requirements

- Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
- Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
- Write a new test suite named `"The menu"`.
- Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
- Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
- Write a test suite named `"Initial Entries"`.
- Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
- Write a test suite named `"New Feed Selection"`.
- Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
- No test should be dependent on the results of another.
- Callbacks should be used to ensure that feeds are loaded before they are tested.
- Implement error handling for undefined variables and out-of-bound array access.
- When complete - all of your tests should pass.

## Testing Results

![alt Testing Results](https://github.com/claudiainbytes/feedreader-jasmine-testing/blob/master/about/screenshot.png)

## References

- [Jasmine Behavior-Driven Javascript ](https://jasmine.github.io/)
- [Jasmine Cheatsheet](https://devhints.io/jasmine)
- [Unit Testing with Jasmine: The Very Basics](https://dev.to/aurelkurtula/unit-testing-with-jasmine-the-very-basics-74k)
- [Jasmine: Understanding the Difference between beforeAll and beforeEach](http://breazeal.com/blog/jasmineBefore.html)
- [Asynchronous Testing With Jasmine](https://metabroadcast.com/blog/asynchronous-testing-with-jasmine)

## How to install

Clone this project in your local machine, go into the folder, and open index.html in a browser to play:
```
  git clone https://github.com/claudiainbytes/feedreader-jasmine-testing

```

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

For src folder (no-optimized site/in process to be optimized):

  ```bash
  $> cd /path/to/feedreader-jasmine-testing
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
