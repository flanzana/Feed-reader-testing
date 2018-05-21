# Feed Reader Testing
Feed Reader Testing has been made as a project for Udacity nanodegree *Front-End Web Developer*.

## Project overview
 In this project I was given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! I needed to write all other test suites.

## Instructions
- Open the file `*/index.html` in your browser (Google Chrome is recommended).
- Tests are written in the file `*/jasmine/spec/feedreader.js`.
- All of the tests should pass.

## Test suites in this project

#### RSS Feeds
- Test makes sure that the `allFeeds` variable has been defined and that it is not empty.
- Test loops through each feed in the `allFeeds` object and ensures it has a name defined and that the name is not empty.
- Test loops through each feed in the `allFeeds` object and ensures it has an URL defined and that the URL is not empty.

#### The Menu
- Test ensures the menu element is hidden by default.
- Test ensures the menu changes visibility when the menu icon is clicked.

#### Initial Entries
- Test ensures when the `loadFeed` function is called and completes its work, there is at least a single `.entry` element within the `.feed` container.

#### New Feed Selection
- Test ensures when a new feed is loaded by the `loadFeed` function that the content actually changes.

## Sources
- JavaScript Testing [course](https://www.udacity.com/course/ud549)
- Feed Reader Testing [Project Rubric](https://review.udacity.com/#!/projects/3442558598/rubric)
- [Required project assets](http://github.com/udacity/frontend-nanodegree-feedreader)
- [Jasmine documentation](http://jasmine.github.io)