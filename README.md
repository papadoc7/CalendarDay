### Calendar Challenge 

This challenge is to render a series of events on a single day calendar, similar to what you’ll find on your favourite calendar app. 

Your solution should accept as input an `Array` of `events` . An `event` is a JavaScript Object that contains a start time and an end time as follows: 

`const events = [{start: 30, end: 120}, {start: 300, end: 330}, {start: 290, end: 330}]`
 The `start` and `end` are minutes since 9am, so 30 is 9:30 am, 120 is 11am, etc. Your calendar view is expected to only show the working hours window of 9am-6pm for one day. 

- The calendar is to be laid out vertically so that later events appear further down the page.
-  No events should visually overlap on the calendar.
-  If two or more events collide then they should have equal width.
-  Include a function called `renderDay` that is accessible globally. It should take 1 argument - `events` - an array of `Event` s as described above. Running 

```
window.renderDay([{start: 30, end: 120}, {start: 300, end: 330}, {start: 290, end: 330}])
```

in the browser console should render 3 events in your calendar. 

#### Rules: 

-------

- Use of CSS Grid is not allowed for the rendering of events - this challenge is meant to primarily showcase your JS ability.

- You may use any third party libraries or frameworks that you deem appropriate, but you must provide the core of the implementation. 

- You may build your CSS/JS through a compiler but please include both the compiled and uncompiled code in your submission.
- Your solution must work without a back-end server. It should have no dependencies other than HTML, CSS and JS. This means provide a compiled version of the code or one that runs correctly when you open the html file directly in a browser. 

- You should also provide an uncompiled version, if you are using 'npm' or 'yarn' please include the package.json file. Do not provide the full 'node_modules' folder 

#### Suggestions: 

---

- This challenge will be the first time we get to see your technical skills. We suggest you use the tools you are most experienced with.

- You should write production quality code, providing tests and comments where necessary. Even though this is just a coding challenge, treat it in the same way you would a core feature of a product.  

- Start early and make sure you give yourself enough time to try a different approach if you get stuck. 

