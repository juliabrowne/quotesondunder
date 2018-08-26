# Quotes on Dunder

QoD is a WordPress theme forked from Underscores. It randomizes quotes from the TV show "The Office" and sorts them by specific categories and tags. QoD also allows site visitors to submit their own quotes (which will then have to be approved by a moderator before being posted).

## Main components:

* Fetching new quotes without page refresh:
    * calling the ajax method on button click with javascript, then using html() to change the html within a specified element
    * pushing the current page's slug onto url, which allows the user to navigate to a previously loaded quote by hitting the back button

## To Use:

* download files
* add files to `wp-content/themes` directory
* run npm install inside theme directory
* and voilà!