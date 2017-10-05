# ICM-2017
Syllabus for ITP Foundation Course Introduction to Computational Media

### Summary
* 1 -- Introduction and Drawing
* 2 -- Animation Variables
* 3 -- Interaction If Statements, Repeat Loops
* 4 -- Functions: the basics
* 5 -- Objects and Arrays
* 6 -- Serial and DOM: events and callback function
* 7 -- Data
* 8 -- Video and Sound
* 9 -- Extra Synthesis Workshop -- All sections meet Friday, October 27, 11am-2pm!
* 10 -- Mobile
* 11 -- Other Topics + Final Project Proposals
* 12 -- Beyond p5.js + Final Project Proposals
* 13 -- One on one speed user testing / feedback
* 14 -- Final Project Presentations



## Listserv
- [Sign up for the ICM google group](https://groups.google.com/a/itp.nyu.edu/group/icm/)

## p5.js
- This year we are using [p5.js](http://www.p5js.org/), a JavaScript framework for creative coding.  Check out the [new web editor for p5.js](https://alpha.editor.p5js.org/).

## Section specific info
* [office hours, scheduling, and contact info](https://github.com/ITPNYU/ICM-2017/blob/master/sections.md)

## Homework Wikis
- Allison, Monday, 6:30-9:00: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Allison-Monday)
- Allison, Wednesday, 12:10–2:40: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Allison-Wednesday)
- Dano, Wednesday, 3:20-5:50: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Dano-Wednesday)
- Mimi, Tuesday, 12:10-2:40: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Mimi-Tuesday)
- Shawn, Wednesday, 12:10-2:40: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Shawn-Wednesday)
- Shiffman, Wednesday, 9:00-11:30: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Shiffman-Wednesday-1)
- Shiffman, Wednesday, 3:20-5:50: [Homework](https://github.com/ITPNYU/ICM-2017/wiki/Homework-Shiffman-Wednesday-2)


## Videos
- [Kadenze course](https://www.kadenze.com/courses/introduction-to-programming-for-the-visual-arts-with-p5-js/info)
- [Shiffman YouTube playlist](https://www.youtube.com/user/shiffman/playlists?sort=dd&view=50&shelf_id=14). The videos on YouTube display skippable ads.  If you would like downloadable, non-ad versions of the videos, please contact Dan.

## Books
- [Make: Getting Started with p5.js: Making Interactive Graphics in JavaScript and Processing](http://amzn.to/1PmztVt) is probably your best bet for now if you are looking for a book. [Free through NYU library](https://ebookcentral.proquest.com/lib/nyulibrary-ebooks/detail.action?docID=4333728)
- If you are interested in some supplemental reading on HTML and CSS, The [HTML & CSS book](http://www.htmlandcssbook.com/) is a nice one.

## Example Code
- [Getting Started with p5.js code](https://github.com/lmccart/gswp5.js-code)
- [Learning Processing code ported to p5.js](https://github.com/shiffman/LearningProcessing-p5.js)
- [Video lesson accompanying code](https://github.com/CodingRainbow/Rainbow-Code/tree/master/p5.js)

## Extra Help
- [Research Resident Office Hours](http://itp.nyu.edu/residents/contact-the-residents/)
- [Cassie Office Hours](https://github.com/ITPNYU/ICM-2017/wiki/Cassie-Office-Hours) -- (Cassie is the lead developer of the p5.js web editor so bring your bugs and questions about that!)
- ICM Help Sessions:
- Tuesdays,  6:45pm - 8:45pm, Meeting Room, with residents Mathura & Leon
- Fridays 1:00pm - 2:30pm, Room 20, with residents Lisa & Aarón

## Inspirational Projects
- [Help contribute to this wiki!](https://github.com/ITPNYU/ICM-2017/wiki/Inspiration)

## Resources
- [p5.js reference](http://p5js.org/reference)
- [p5.js forum](http://forum.processing.org/two/)
- [p5.js tutorials](https://p5js.org/learn/)
- [Getting Started with p5.js](http://amzn.to/1PmztVt) - O'Reilly book
- [Intro to Visual Programming with p5.js](https://www.kadenze.com/courses/introduction-to-programming-for-the-visual-arts-with-p5-js) - online video tutorials (free with signup)
- There are [many additional resources on the Resources wiki page](https://github.com/ITPNYU/ICM-2017/wiki/Resources).

## Syllabus

### 1 -- Introduction and Drawing
* What is computational media?
  * What is programming?
  * How can I apply programming to _____________?
  * As a ____________, why would I want or need to write software?
  * [Example projects](https://github.com/ITPNYU/ICM-2017/wiki/Inspiration).
* Programming language discussion
  * General discussion of programming languages
  * History of creative coding frameworks
      * Processing and p5.js (and what's processing.js?): [What is p5.js video](https://www.youtube.com/watch?v=8j0UDiN7my4&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=1)
      * openframeworks, cinder
      * max/msp dataflow programming
      * How does arduino fit in?
* p5.js in the context of the browser
  * Landscape of HTML, CSS, and JavaScript
  * Other JS frameworks
  * Server-side vs. client-side
  * What is the difference between p5 and JavaScript?
* Participating in an open-source community
  * What are git and github?
  * When should you post to a forum vs. file a github issue?
  * Who makes these things?
  * [p5.js working group mailing list](http://groups.google.com/forum/#!forum/p5xjs-working-group)
* Getting started, your first program
  * Drawing with numbers: [video tutorial](https://www.youtube.com/watch?v=D1ELEeIs0j8&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=2)
  * Shape and color functions: [video tutorial](https://www.youtube.com/watch?v=9mucjcrhFcM&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=3)
  * `setup()` and `draw()`
  * [p5.js reference](http://p5js.org/reference)
* <a id="optional-1">Optional viewing / reading:</a>
  * [Pick an Eyeo Talk that looks interesting](https://vimeo.com/eyeofestival/)
  * [Introductory p5.js videos](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
  * [FORM+CODE: Introduction and What is Code?](http://formandcode.com)
  * [As We May Think](http://www.theatlantic.com/magazine/archive/1945/07/as-we-may-think/303881/), Vannevar Bush
  * [Long Live the Web](http://jblomo.github.io/webarch253/slides/Long_Live_the_Web.pdf), Tim Berners-Lee
* Very extra painting links
  * [For more about color](https://programmingdesignsystems.com/color/a-short-history-of-color-theory/index.html)
  * [For more about shapes (specifically "custom shapes" with vertices and bezier curves)](https://programmingdesignsystems.com/shape/custom-shapes/index.html#custom-shapes-pANLh0l)
  * [p5 playground (by Yining)](http://yining1023.github.io/p5PlayGround/)


### 2 -- Animation
- Program flow (what's a function?)
  - Setup, draw, and other events
  - Variation: mouseX and mouseY
  - [video tutorial](https://www.youtube.com/watch?v=RnS0YNuLfQQ&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=5)
- More about variables
  - make your own variables (numbers and strings), [video tutorial](https://www.youtube.com/watch?v=Bn_B3T_Vbxs&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=6)
  - JS objects (variables inside variables), [video tutorial](https://www.youtube.com/watch?v=-e5h4IGKZRY&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=7)
- [random()](http://p5js.org/reference/#/p5/random), [video tutorial](https://www.youtube.com/watch?v=nfmV2kuQKwA&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=9)
- [map()](http://p5js.org/reference/#/p5/map), [video tutorial](https://www.youtube.com/watch?v=nicMAoW6u1g&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=8)
- Transformations
   - `translate()`, `rotate()`, `scale()`, `push()`, `pop()`
   - [translate, rotate, push, pop video tutoral](https://youtu.be/o9sgjuh-CBM)
   - [scale video tutorial](https://youtu.be/pkHZTWOoTLM)
   - [more on technical details](https://youtu.be/IVMvq9rd8dA)
- Examples
  - [random painting](https://alpha.editor.p5js.org/projects/HJg8jfcT3)
  - [mouse controlled painting](https://alpha.editor.p5js.org/projects/r1JeQqa3)
  - [moving circle](https://alpha.editor.p5js.org/projects/Bymv7ca2)

### 3 -- Interaction
- Conditional Statements
    - Boolean expressions
    - if statement
    - relational operators
    - [video tutorial](https://www.youtube.com/watch?v=1Osb_iGDdjk&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=10)
    - Case study, bouncing ball: [video tutorial](https://www.youtube.com/watch?v=LO3Awjn_gyU&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=11)
    - else, else if, AND, OR [video tutorial](https://www.youtube.com/watch?v=r2S7j54I68c&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=12)
    - boolean variables [video tutorial](https://www.youtube.com/watch?v=Rk-_syQluvc&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=13)
    - buttons, rollovers, switches
- Loops (while and for)
    - while and for [video tutorial](https://www.youtube.com/watch?v=cnRD9o6odjk&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=14)
    - nested loops [video tutorial](https://www.youtube.com/watch?v=1c1_TMdf8b8&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=15)
- Examples
    - Motion
      - [bouncing ball](https://alpha.editor.p5js.org/projects/BJKWv5Tn)
      - [10PRINT](https://alpha.editor.p5js.org/projects/rkHKL962)
    - GUI
      - [circle rollover](https://alpha.editor.p5js.org/projects/H1kCSqah)
      - [square rollover](https://alpha.editor.p5js.org/projects/rkLfL56h)
      - [button hold down](https://alpha.editor.p5js.org/projects/S16-H9pn)
      - [button switch](https://alpha.editor.p5js.org/projects/Sywrrqa2)
      - [quadrant rollover](https://alpha.editor.p5js.org/projects/Hki1I5ah)
      - [rollover with fade](https://alpha.editor.p5js.org/projects/SkPsHcph)
      - [draggable](https://alpha.editor.p5js.org/projects/B13wH5T3)
      - [knob](https://alpha.editor.p5js.org/projects/HkfFHcp2)
      - [slider](https://alpha.editor.p5js.org/projects/H1LXU9ah)

### 4 -- Functions: the basics
- Calling vs. defining
- Modularity: [video](https://www.youtube.com/watch?v=wRHAitGzBrg&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=16)
   - [bouncing ball with functions example](https://alpha.editor.p5js.org/projects/H1Oq4qta)
- Arguments and parameters
   - [dice no functions example](https://alpha.editor.p5js.org/projects/ryx70m5tT)
   - [dice w/ functions example](https://alpha.editor.p5js.org/projects/S1R44qtT)
- Re-usability: [video](https://www.youtube.com/watch?v=zkc417YapfE&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=17)
   - [robots from Getting Started](https://alpha.editor.p5js.org/projects/rylf4S5K6)
- Return types: [video](https://www.youtube.com/watch?v=qRnUBiTJ66Y&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=18)
   - [implementing distance function example](https://alpha.editor.p5js.org/projects/HJgR7UcKa)
- Recursion
   - [video tutorial](link coming soon -- remind me somebody!)
   - [recursion](https://alpha.editor.p5js.org/projects/Hyevi8ct6)
- Optional Readings:
  - [Work of Art in the Age of Mechanical Reproduction](http://www.berk-edu.com/VisualStudies/readingList/06b_benjamin-work%20of%20art%20in%20the%20age%20of%20mechanical%20reproduction.pdf), Walter Benjamin

* Object Video tutorials:
* Array Video tutorials:
    * [What is an array?](https://www.youtube.com/watch?v=VIQoUghHSxU)
    * [Arrays and loops](https://www.youtube.com/watch?v=RXWO3mFuW-I)
    * More videos about arrays coming soon. . .
* [Learning Processing Chapter 8 on Objects translated to p5](https://shiffman.github.io/Learning-p5.js/ch08.html)

### 5 -- Objects and Arrays
* Object-Oriented Programming with Classes in JavaScript
    - [Mozilla Classes reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)
    - [OOP with p5.js tutorial](https://shiffman.github.io/Learning-p5.js/ch08.html)
    - Video: [6.1 Intro to ES6 OOP](https://www.youtube.com/watch?v=xG2Vbnv0wvg)
    - Video: [6.2 Writing a Class](https://www.youtube.com/watch?v=T-HGdc8L-7w)
    - Video: [6.3 Constructor Arguments](https://www.youtube.com/watch?v=rHiSsgFRgx4)
    - More videos about objects coming soon. . .
    - [Two Gravity Ball Objects Example](http://alpha.editor.p5js.org/icm/sketches/BkyUQp1nb)
* What is an array? [video tutorial 7.1](https://www.youtube.com/watch?v=VIQoUghHSxU&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=20)
  * declaring, initializing
  * numeric indices
  * [A Snake Following the Mouse](http://alpha.editor.p5js.org/projects/Sy1ECGcA)
  * arrays and for loops: [video tutorial 7.2](https://www.youtube.com/watch?v=RXWO3mFuW-I&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=21)
  * `length` property
* An array of objects! Old video, no classes! [video tutorial 6.3](https://www.youtube.com/watch?v=pGkSHeEZLMU&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=22)
  * [Interactive Stripes](http://alpha.editor.p5js.org/icm/sketches/B1ja76khW)
* Adding and deleting from an array, `push()` and `splice()` Old video, no classes! [video tutorial. 6.5](https://www.youtube.com/watch?v=EyG_2AdHlzY&index=24&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA)
  * [MousePressed Adding New Gravity Ball Objects](http://alpha.editor.p5js.org/icm/sketches/B1ja76khW)
* Clicking on objects Old video, no classes! [video tutorial 6.7](https://www.youtube.com/watch?v=DEHsr4XicN8&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=26)
  * [An Array of Buttons](http://alpha.editor.p5js.org/icm/sketches/BkaTNak3Z)
* Checking objects intersecting with other objects Old video, no classes! [video tutorial 6.9](https://www.youtube.com/watch?v=uAfw-ko3kB8&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=28), Old video, no classes!  [video tutorial 6.10](https://www.youtube.com/watch?v=GY-c2HO2liA&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=29)
   * [Checking Objects Intersection]http://alpha.editor.p5js.org/icm/sketches/S1BbBT13b)
* loading images for objects Old video, no classes! [video tutorial 6.11](https://www.youtube.com/watch?v=FVYGyaxG4To&list=PLRqwX-V7Uu6Zy51Q-x9tMWIv9cueOFTFA&index=30)
  * [MousePressed Adding New Images](http://alpha.editor.p5js.org/icm/sketches/SJzKEak3W)
* [Optional quiz to test your knowledge](https://itpnyu.github.io/ICM-Quizzes/week5-objects-arrays/)


### 6 -- Serial and DOM: events and callback function
- Review events -- mousePressed, keyPressed
- Review Serial, introduce callback
* [All video tutorials](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bI1SlcCRfLH79HZrFAtBvX)
- [Tutorial: Beyond the Canvas, using p5.dom](https://github.com/processing/p5.js/wiki/Beyond-the-canvas)
- [Tutorial: Intro to HTML/CSS basics](https://github.com/processing/p5.js/wiki/Intro-to-HTML-and-CSS#css)
- DOM elements - [p5.dom reference](http://p5js.org/reference/#/libraries/p5.dom)
    - `createP()`
    - `createButton()`
    - `createSlider()`
- Callbacks
    - `button.mousePressed(callback);`
- `style()` -- low key intro to CSS
- [CSS Reference](http://www.blooberry.com/indexdot/css/propindex/all.htm)

### 7 -- Data
* [All video tutorials](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6a-SQiI4RtIwuOrLJGnel0r)
- [Tutorial: loading external data with p5.js](https://github.com/processing/p5.js/wiki/Loading-external-files:-AJAX,-XML,-JSON)
- [Tutorial: more about data and APIs](http://shiffman.net/a2z/data-apis/)
- JSON and APIs (and more on callbacks!)
- [Word Counting](http://shiffman.net/a2z/text-analysis/)
- Tabular data
- Maps, see: [Mappa](https://github.com/cvalenzuela/Mappa)
- Additional Reading:
  - [Art and the API](http://blog.blprnt.com/blog/blprnt/art-and-the-api), Jer Thorp
  - [The Anxieties of Big Data](http://thenewinquiry.com/essays/the-anxieties-of-big-data/), Kate Crawford
  - [Sentencing Guideline From Surya](https://www.washingtonpost.com/news/monkey-cage/wp/2016/10/17/can-an-algorithm-be-racist-our-analysis-is-more-cautious-than-propublicas/)

### 8 -- Video and Sound
* [Video tutorials on video](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aKKsDHZdDvN6oCJ2hRY_Ig)
* [Video tutorials on sound](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6aFcVjlDAkkGIixw70s7jpW)
- [p5.sound reference](http://p5js.org/reference/#/libraries/p5.sound)
- [Video/capture: p5.MediaElement reference](http://p5js.org/reference/#/p5.MediaElement)
- Sound
- Live capture
- Movie playback
- Video Assignment

### 9 -- Extra Synthesis Workshop -- All sections meet Friday, October 27, 11am-2pm!
* Meet in the ITP Lounge
* Pizza will be served
* Details TBA

### PROJECT RUNWAY

### 10 -- Mobile
- Workflow and process, get a previous sketch running on a device
- Touch interaction
  - [Single Touch](http://alpha.editor.p5js.org/projects/H1a1YWOgl)
  - [Multi Touch](http://alpha.editor.p5js.org/projects/HkDY43yxl)
- Events
  - [Device Moved](http://alpha.editor.p5js.org/projects/BysXo-dgx)
  - [Device Turned](http://alpha.editor.p5js.org/projects/ryMwSnyxx)
  - [Device Shaken 1](http://alpha.editor.p5js.org/projects/rkmqU2Jee)
  - [Device Shaken 2](http://alpha.editor.p5js.org/projects/rJWwujwxg)
- Sensors
  - [Rotation (Gravity)](http://alpha.editor.p5js.org/projects/Hylv2b_xl)
  - [Acceleration (3D)](http://alpha.editor.p5js.org/projects/BJxoCbdxx)
  - [Geolocation 1: lookup lat lon](https://alpha.editor.p5js.org/projects/HkQ8kMdee)
  - [Geolocation 2: track lat lon](https://alpha.editor.p5js.org/projects/SyfolGuex)
- [Hammer.js](http://hammerjs.github.io/)
  - [Swipe events](http://alpha.editor.p5js.org/projects/HyEDRsPel)
  - [Swipe force](http://alpha.editor.p5js.org/projects/rkOj4bueg)
  - [Pinch and rotate](http://alpha.editor.p5js.org/projects/SJpBDW_gg)
- Remote debugging:
  - [Android remote debugging](https://developers.google.com/web/tools/chrome-devtools/remote-debugging/?hl=en)
  - [iOS remote debugging](https://developer.apple.com/library/content/documentation/AppleApplications/Conceptual/Safari_Developer_Guide/GettingStarted/GettingStarted.html)
  - [Generic remote debugging](https://jsconsole.com/)
- [Using the viewport meta tag to control layout on mobile browsers](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)
- Homework: Prepare a final project proposal.  See you section's wiki.

### 11 -- Other Topics + Final Project Proposals
- **See your individual section's proposal schedule on your wiki**
- Possible topics
   - more on pixels
   - more on data
   - setTimeout, setInterval
   - WebGL - [tutorial](https://github.com/processing/p5.js/wiki/Getting-started-with-WebGL-in-p5)

### 12 -- Beyond p5.js + Final Project Proposals
- **See your individual section's proposal schedule on your wiki**
- Life beyond p5.js
  - Take ICM into the spring semester courses
  - Other JS libraries?
  - Coding outside the p5 IDE? ([local server tutorial](https://github.com/processing/p5.js/wiki/Local-server)), [video tutorial](https://www.youtube.com/watch?v=UCHzlUiDD10)
  - [More HTML/CSS](https://github.com/processing/p5.js/wiki/Intro-to-HTML-and-CSS)
  - What is server side programming for?
    - [Database a service](http://shiffman.net/a2z/firebase/) controlled by p5.js client.
    - [web sockets for real-time communcation](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6b36TzJidYfIYwTFEq3K5qH)
    - [Basics of node](http://shiffman.net/a2z/server-node/), [making an API in Node](http://shiffman.net/a2z/node-api/)
  - [Processing](http://processing.org)
  - Open source
    - How do artists make and adapt tools for themselves and their communities, like Processing, p5.js, openFrameworks, etc?
  - How do you get involved with this?

### 13 -- One on one speed user testing / feedback
- This week you will "user test" your project with fellow classmates. You must have some implementation that you can test completed by this time.  User testing can mean different things for different projects. For a game, it can mean that the user tries to play it. For an art piece, it could mean showing it to a classmate and asking for them to say what they think it is about or how it made them feel. We'll show projects in a "one on one" / round robin / speed dating-style session. 5 minutes then switch. You cannot not explain your project, just show and let the user try it and give you feedback. Then you can answer questions.  User testing schedule will be provided on a wiki.

### 14 -- Final Project Presentations
- Please add your link to your final project documentation on your section's wiki.


# Policies

## Evaluation

Grades will be determined according to the following breakdown:
* Regular Assignments 40%
* Participation and Attendance 40%
* Final Project 20%

Please see ITP's statement on [Pass/Fail](http://help.itp.nyu.edu/academic-policies/pass-fail) which states that a "Pass" is equivalent to an "A" or a "B" while anything less would be considered a "Fail".

We will have weekly assignments that are relevant to material from the previous class. These assignments are required and you should be prepared to show/talk about them in class. It is expected that everyone in the class will create and maintain a blog for their assignments.

Attendance is mandatory. Please inform your teacher via email if you are going to miss a class. Two unexcused absences is cause for failing the class. (An unexcused lateness of 10 minutes or more is equivalent to 1/2 an absence.)

This class will be participatory, you are expected to participate in discussions and give feedback to other students both in class and participate with their projects. This (along with attendance) is 40% of your grade.

Class will culminate with final projects. You are expected to push your abilities to produce something that utilizes what you have learned in the class that is useful in some manner to yourself or the world. This will comprise 20% of your grade.


Mantras By James
----------------
- "Practice is the best of all instructors." - computation requires practice
- "An agreeable companion on a journey is as good as a carriage." - look to your classmates for help too
- "While we stop to think, we often miss our opportunity." - sometimes you need to take a leap of faith
- "When two do the same thing, it is not the same thing after all." - encourage students with similar ideas
- "The bow too tensely strung is easily broken." - don't get too stressed out
- All of these are from Plubius Syrus.(42 B.C.)

Previous Years
--------------
- [Old 2015 Syllabi and links](https://github.com/ITPNYU/ICM-2015/)
- [Old 2014 Syllabi and links](https://github.com/ITPNYU/ICM-2014/)
- [Old 2013 Syllabi and links](https://github.com/ITPNYU/ICM-2013/)
- [Old 2012 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F12)
- [Old 2011 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F11)
- [Old 2010 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F10)
- [Old 2009 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F09)
- [Old 2008 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F08)
- [Old 2007 Syllabi and links](http://itp.nyu.edu/varwiki/Syllabus/ICM-All-F07)
