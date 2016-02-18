---
title: "New features in ES6"
author: Saundie Weiss
date: 2016-02-10
template: article.jade
---

We started exploring the new features that rolled out in ES6. We're using [Babel, a JavaScript complier](https://babeljs.io/).

<span class="more"></span>

ES6 defines two new ways to store values, `let` and `const`. They are block scoped, so their scopes are only defined within `{}`.

Another new feature is the arrow notation. This is a new way to write functions. Arrow notation is less code to write and simpler. They are always anonymous and lexically bind `this`, which means that `this` will bind to the parent function.

You can use the arrow notation like this:

```
function myCalc(){
  this.total = 0;
  let someArr = [1,2,3,4];

  someArr.forEach((item) => {
    this.total += item;
    });
  }
  ```

The feature that I'm most excited about is the `for...of` loop. This loop will iterate of "iterable objects" (MDN), which means that we can use it for objects **and** arrays. Before, we could only use the `for...in` loop to loop through objects.

I know there are more to explore, but for now, these are the features I'm most excited about!
