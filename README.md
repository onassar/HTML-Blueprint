HTML-Blueprint
===
This library is meant to act as a jumpoff or starter point for small and large
projects alike. Focusing on the front end entirely, it makes use of the
[JS-Fondation](https://github.com/onassar/JS-Foundation) library, as well as
performing the following:

 - Defining the doctype (HTML5)
 - Defining the charset
 - Hot linking to a reset style sheet
 - Booting in Google Analytics
 - Defining Open Graph meta tags/information
 - Loading in the minified
[JS-Fondation](https://github.com/onassar/JS-Foundation) library
 - Loading in the HTML5 shiv (for non-modern browsers)
 - Booting in the required scripts after the DOM is ready (including, by default
[MooTools]()http://mootools.net/)
 - Processing the stack of functions that have been queued up

The above events are included in this blueprint as they were what I found helped
me most when putting together the client side of both small and larger
applications. Allowed me to get up and running real fast, so hopefully this
comes in useful for others.
