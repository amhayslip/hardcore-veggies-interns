# Coding Exercise for Front-End Developer candidates

## Introduction

This exercise will help the hiring team at Spredfast gauge your level of front-end coding experience (HTML, CSS & JavaScript).

Please budget about two hours of actual coding time to complete the project. We realize that's a tight constraint, but we'd like to be respectful of your time while still allowing you to produce enough code for us to make a fair assessment of your skills. Try to ensure that the finished product represents your coding abilities. You are not necessarily expected to fully finish within the time limit. We'd much rather review high-quality, incomplete work than rushed, completed work.

We've created a few starter files that you should flesh out:

* [index.html](index.html)
* [style.css](css/style.css)
* [script.js](js/script.js)

and a [PSD](Leaderboard.psd) to use as a mockup.

## Requirements

You will build a "Hardcore Produce" leaderboard, which is a list of the top five hardcore veggie names paired with the number of times that they have been mentioned on Twitter or Facebook.

For simplicity's sake, we've created an API and included some starter code (see [script.js](js/script.js)). The API provides a `Poller()` class with a `.poll()` method that allows you to set some options and provide a callback function that will be called when the poller returns data.

Upon each poll, the API will send an array of objects to your callback function. Each object will contain an item name and its associated count, sorted descending by count.

The leaderboard that you build should satisfy these basic requirements:

* Visually adhere to the provided [PSD](Leaderboard.psd).
* Every 15 seconds, update the leaderboard to show the latest produce names and counts, sorted descending by count.

When you're finished, please send your work to your Spredfast dev contact as a .zip file or (preferably) a link to a public repo on GitHub.

## Questions?

Please use your best judgment to interpret the requirements above. However, if you're stuck with questions, feel free to email your Spredfast dev contact. There are no bad questions (other than, "What does JavaScript mean?").
