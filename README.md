# JavaScript Code Challenge

Welcome to Rhove's JavaScript code challenge! We've already created all the boilerplate for you, so you can spend your time solving problems rather than setting up.

You have one week to complete this challenge and it should take you **no longer than 4 hours**. We want to be respectful of your time, so at the four-hour mark, submit your challenge and go celebrate a job well done. If there's work you would have completed if you'd had more time (and the app was meant for production), feel free to write that down and submit it along with your code. 

Let us know if you have any questions, and good luck!

## Getting Started

    $ npm i
    $ npm start

## Challenge Instructions

The requirements for your application are as follows:

1) Displays a list of at least four XKCD comics, acquired via the XKCD API endpoint. 
    * Note: XCKD's API doesn't have CORS support. Using any-api.com's version of the API gets around this issue.
    * `https://any-api.com:8443/http://xkcd.com/{COMIC_ID}/info.0.json` where `COMIC_ID` is just a numeric identifier of the comic you'd like to pull.
    * [API console](https://any-api.com/xkcd_com/xkcd_com/console/_comicId_info_0_json/GET)
2) Includes the title, date published, and image for each comic.
3) The list of comics is arranged in a grid.
4) Comics are sorted by date with the most recent comics first.
5) Includes a checkbox that, when checked, sorts the comic strips by date so the least recent comics are first.
6) When the checkbox is unchecked, the comics revert to most recent first.
7) Styling for the page is done using using the [styled-components](https://www.styled-components.com/) library.


## Evaluation Criteria

* Runs in Chrome. Don't worry about browser compatibility for this challenge.
* Includes more than one commit, each with a thoughtful commit message.
* Work is logically grouped into commits.
* `npm i` downloads all dependencies.
* `npm start` runs the application.
* React components are organized into separate files.
* Styling is used to enhance the page, and done so in reusable components.
* No console errors.
* Meets the challenge requirements.

## Code Challenge Submission

Send a link to your GitHub repository to your contact at Rhove, and you're all done!
