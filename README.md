Udacity Neighborhood Map - Palermo Cultural
===========================================

The purpose of this project is create a SPA(Single Page Application) from a specific neighborhood that shows interesting spots using Google Maps Api and 3rd party APIs.

I make a cultural project where shows venues related to arts, music, museums, dance classes, bookstores, theaters and more in Palermo Neighborhood in Bogotá, Colombia.

![alt palermocultural](https://github.com/claudiainbytes/palermo-neighborhood-map/blob/master/about/screenshot.png)

## SPA Features

Libraries

- Knockout.JS as MVVM framework to organize the code
- jQuery for DOM manipulation
- Bootstrap 3.3.6 as CSS Framework
- Perfect-scrollbar to scroll in the locations nav list
- Slick.JS to slide info in each infoWindow

APIs

- Google Maps API
- Google StreetView Image API
- Firebase database to store JSON data

Google APIs requires a project name and a key to access several web services.

## Demo

If you want to play this project, click here: [Palermo Cultural ](https://claudiainbytes.github.io/palermo-neighborhood-map/src)

## Funcionality

This application does:

- Loads a map of a specific area according to lat and long coordinates
- For each location show markers

- Clicking on each marker, shows a infoWindow

![alt infowindow](https://github.com/claudiainbytes/palermo-neighborhood-map/blob/master/about/screenshot1.png)

- Shows a list of locations on the left nav bar
- Clicking in a list element, shows the venue infoWindow

![alt locations](https://github.com/claudiainbytes/palermo-neighborhood-map/blob/master/about/screenshot2.png)

- Watching the street nearest to the location using Google Street View

![alt streetview](https://github.com/claudiainbytes/palermo-neighborhood-map/blob/master/about/screenshot3.png)

- Filter locations by title of location

![alt locations](https://github.com/claudiainbytes/palermo-neighborhood-map/blob/master/about/screenshot4.png)




## How to install

Clone this project in your local machine, go into the folder, and open index.html in a browser to play:
```
  git clone https://github.com/claudiainbytes/palermo-neighborhood-map

```

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

For src folder (no-optimized site/in process to be optimized):

  ```bash
  $> cd /path/to/palermo-neighborhood-map/src
  $> python -m SimpleHTTPServer 8080
  ```

For dist folder( optimized site):

  ```bash
  $> cd /path/to/palermo-neighborhood-map/dist
  $> python -m SimpleHTTPServer 3000
  ```

1. Open a browser and visit localhost:8080
2. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

For src folder (no-optimized site/in process to be optimized):
  ```bash
  $> cd /path/to/palermo-neighborhood-map/src
  $> ./ngrok http 8080
  ```

For dist folder( optimized site):

  ```bash
  $> cd /path/to/palermo-neighborhood-map/dist
  $> ./ngrok http 3000
  ```
# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What will I learn?

You will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How will this help my career?

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# How will I complete this project?

Review the Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)

1. Take the JavaScript Testing [course](https://www.udacity.com/course/ud549)
2. Download the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
3. Review the functionality of the application within your browser.
4. Explore the application's HTML (**./index.html**), CSS (**./css/style.css**) and JavaScript (**./js/app.js**) to gain an understanding of how it works.
5. Explore the Jasmine spec file in **./jasmine/spec/feedreader.js** and review the [Jasmine documentation](http://jasmine.github.io).
6. Edit the `allFeeds` variable in **./js/app.js** to make the provided test fail and see how Jasmine visualizes this failure in your application.
7. Return the `allFeeds` variable to a passing state.
8. Write a test that loops through each feed in the `allFeeds` object and ensures it has a URL defined and that the URL is not empty.
9. Write a test that loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
10. Write a new test suite named `"The menu"`.
11. Write a test that ensures the menu element is hidden by default. You'll have to analyze the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
12. Write a test that ensures the menu changes visibility when the menu icon is clicked. This test should have two expectations: does the menu display when clicked and does it hide when clicked again.
13. Write a test suite named `"Initial Entries"`.
14. Write a test that ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.
15. Write a test suite named `"New Feed Selection"`.
16. Write a test that ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.
17. No test should be dependent on the results of another.
18. Callbacks should be used to ensure that feeds are loaded before they are tested.
19. Implement error handling for undefined variables and out-of-bound array access.
20. When complete - all of your tests should pass.
21. Write a README file detailing all steps required to successfully run the application. If you have added additional tests (for Udacious Test Coverage),  provide documentation for what these future features are and what the tests are checking for.
