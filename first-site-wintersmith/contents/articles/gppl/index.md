---
title: Galvanize Ping Pong League
author: Saundie Weiss
date: 2016-01-08
template: article.jade
---

Before the holidays, we completed another project. This was a group project, and it was really cool to work with a team. We created Galvanize Ping Pong League (GPPL).

<span class="more"></span>

[You can view the application here.](https://galvanize-ping-pong-league.herokuapp.com/)

[You can watch screencast demo here.](https://vimeo.com/149898674)

GPPL is a score-tracking application for ping pong games. Users are able to use the application with or without a login. The games are logged in a database and wins/losses are tracked with users if they create accounts.

Users can see standings for the top ten rankings in the database on the homepage. The homepage has top five Reddit articles about table tennis.

Another feature of this application is the integration with Slack. We set up a separate Slack channel that notifies users when a match has been logged. It shows the scores in the Slack channel.

The main parts of this application that I worked on were pulling in the Reddit API and generating a list of articles for the homepage and setting up the Slack integration. I also helped set up an AJAX call to allow users to update their own user information.

My favorite part of this project was setting up the Slack integration. I really enjoy working with integrations and making applications more valuable for users.

##### More [Express](http://expressjs.com/)

We are one week into the new year, and we have definitely hit the ground running since the holiday break.

We have been building applications using Express. I’m trying to get into Express every single day to reinforce setting up the application. After working with it this week, it’s finally starting to click. I’ve set up simple applications that allow users to sign up, sign in, and sign out.

We added Knex to it, too, which connects SQL. This took me a little bit to figure out, but I am really excited about it because now we can connect our databases. We are working with Postgres. I really like it but their documentation is dense! This will take some practice. I really want to master working with Postgres.

We were introduced to Bcrypt this week. Bcrypt is how we hash passwords. It’s a node module that we require into Express, and it’s pretty simple to run. Security is really important in web applications, and even though we are just working with passwords right now, it’s good to understand how it works.

Another new concept this week that we talked about are promises. Promises are specific to JavaScript and handle asynchronous code. They are objects that handle pending resolutions. We have been refactoring our code to change the callbacks to promises. They seem complicated in theory, but are simpler in implementation.

Yesterday, we worked with cookies and sessions. HTTP Cookies are stored in the browser and are set by the server to store data in the client. They are key-value pairs. Sessions are data identifiers that are connected to a user. These are a little bit harder to understand, but I found this article this morning that gives a good explanation.
