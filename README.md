#P-6 Feed Reader
## Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!


## What will I learn?

You will learn how to use Jasmine to write a number of tests against a pre-existing application. These will test the underlying business logic of the application as well as the event handling and DOM manipulation.

# What Did I learn?

Using the test suite Jasmine is fun and easy. It is straight forward enough to not over complicate things.

## How will this help my career?

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give you the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.

# How to run the App

  1. Download or clone this repository
  2. Open the index.html file in you favourite browser.
  3. If you would like to add tests then open the jasmine folder, Then the spec folder, Then run the feedReader.js file in your favourite      text editor and add or subtract tests.
     
     -or-
     
   Click the Project link in the above description.

# Tests Created

### Created 4 tests suites in feedreader.js.

        1. Checks if RSS feed are present, have URL's, and Names
        2. Checks the default mode of the menu is hidden and that it changes when clicked
        3. Checks the loadFeed function in app.js to see if has brought back at least 1 entry when the page is loaded
        4. Check when calling for new content that new content is actually replacing the old content.
        

        
