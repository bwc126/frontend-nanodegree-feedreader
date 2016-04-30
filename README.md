# Project Overview

## Project 6: Feedreader Testing

**From Udacity:**
>In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

For the student (me, in this case), this project begins and ends with the test suite. The focus is on writing tests to validate and verify each intended aspect of the feedreader's functionality.

## Running
Download or clone the whole repo, and run index.html in a IE8 or later (or equivalent firefox/chrome/etc). Alternately, patiently await the author's use of github pages to allow easy, direct viewing of projects in a browser!

## Components

### The Feed Reader

Feedreader itself uses an RSS to JSON converter API via Udacity, sending off a URL and returning with lists of articles to diplay in sequence (otherwise known as a feed).

### The Test Suite

Validates and verifies each key mechanic of the app.

#### RSS Feeds
We need to make sure at least one feed is defined, with at least a truthy name and URL.
#### The Menu
We ensure the menu is hidden by default, that it shows when its icon is clicked, and that it hides when its icon is again clicked.
#### Initial Entries
Some article entries (at least one) should appear on the page when a feed has been selected and finishes loading.
#### New Feed Selection
Loading one feed and then loading a different one should change what entries are actually loaded on the page.
