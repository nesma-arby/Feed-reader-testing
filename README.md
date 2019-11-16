# Feed Reader Testing Project

## Table of Contents

- [How to run](#run)
- [Jasmine test Cases](#tests)

## How to run

You don't need anything special to run , this project
has Jasmine setup just load index.html .


## Jasmine test Cases

####  All tests inside feedreader.js

- Make sure that all feeds available 
- loops through each feed in the allFeeds object and ensures it has a URL , Name  defined and not empty.
- ensures the menu element is hidden by default.
- ensures the menu changes visibility when the menu icon is clicked .
- ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
- ensures when a new feed is loaded by the loadFeed function that the content actually changes .

