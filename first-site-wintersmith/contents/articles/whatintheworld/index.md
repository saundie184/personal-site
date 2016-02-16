---
title: What in the World
author: Saundie Weiss
date: 2015-11-25
template: article.jade
---

<screenshot>

We completed our first project!

This application is designed to engage middle school students in current news. They will be able to search for news stories by choosing their own search term. Stories are displayed with the newest items on the top. The publication date is also shown, so students can immediately see which stories were published today.

I used AJAX to call the Guardian API to query news articles based on a search term. The categories (sections) are also displayed next to the articles with icons. Since the students can pick any search term, they will be able to see how news stories (from a variety of sections) may contain information that they care about.

I used Bootstrap for the CSS and Bootstrap glyphicons for the icons. I created a map object that matched each section name to the icon. Since the Guardian has a lot of sections, I created a default icon for cases where the section name was not listed in the map. This project gave me more experience with JavaScript, jQuery, APIs, and specifically with handling errors and default cases.

Application: https://whatintheworld.firebaseapp.com/
Screencast demo: https://vimeo.com/146939181

I was very excited to deploy my first application! It feels good to build something that works! I’m currently working on deploying it as a Chrome App. One of the students in my class gave a lightning talk on Chrome Apps. He provided lots of links and a demonstration of how to set it up. I need to make some changes to fix some of the CSS, but it will look pretty sweet when it does work. I’m also hoping that my friend will test this out in her middle school Current Affairs class.
