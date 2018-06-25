# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

# applied  test suites :  

## "RSS Feeds"  test suite : 
1. `allFeeds` variable is defined.
2.  each item in the `allFeeds` object  has a URL defined and that the URL is not empty.
9.  each item in the `allFeeds` object  has a name defined and that the name is not empty.  

## "The menu" test suite : 
1. the menu element is hidden by default. 
2.  the menu display when clicked and  it hide when clicked again.

## "Initial Entries" test suite : 
1. when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

## "New Feed Selection" test suite : 
1. new feed is loaded by the `loadFeed` function that the content actually changes.


- Implement error handling for undefined variables and out-of-bound array access.

