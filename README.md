# Web and Database Technology (CSE1500)

Materials and resources of the 2018/19 [Web and Database Technology course](http://studiegids.tudelft.nl/a101_displayCourse.do?course_id=48438) at TU Delft are listed here. At the moment, only Web topics are covered.

## Todos (instructors)

- Functional email box `cse1500-ewi[at]tudelft.nl`

## Required [REQ] / recommended [REC] tools

- [REC] [Visual Studio Code](https://code.visualstudio.com/) (*VS Code* for short) is the recommended development environment for this course. It is a free and open-source IDE available for all major operating systems. It was originally designed to support node.js programmers (a server-­side JavaScript framework we will soon use in this class), but now has extensions for many major programming languages. Best of all, Visual Studio Code itself is written in JavaScript! It has [integrated source control](https://code.visualstudio.com/docs/editor/versioncontrol) with `git` support out of the box - making it easy to program in pairs. VS Code also offers many extensions (see a guide of how to browse and install them [here](https://code.visualstudio.com/docs/editor/extension-gallery)), we recommend the following:
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint);
  - [JSHint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint);
  - [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer);
  - [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode); a great tool to try out JavaScript snippets without hassle
  - finally, a good [theme](https://code.visualstudio.com/docs/getstarted/themes) for your IDE to make coding more enjoyable is also not a bad idea; [Dracula](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula) is a popular one. If you want to pick based on visuals, head over to [https://vscodethemes.com/](https://vscodethemes.com/).
- [REQ] [node.js](https://nodejs.org/en/)
- [REQ] Modern Web browser such as Chrome, Firefox, Edge, ...
- [REC] [jest](https://jestjs.io/) for JavaScript testing

## Useful online coding platforms

- [Glitch](https://glitch.com/)
- [Codepen](https://codepen.io/#)
- [MDN](https://developer.mozilla.org/en-US/)

## Grading

- Course grade:
  - 40% midterm (covers the 8 Web technology lectures)
  - 40% final exam (covers the 7-8 database technology lectures)
  - 20% assignments
- Requirements: to pass, the overall grade must be **5.8** or higher AND the midterm grade must be at least a **5** AND the final exam grade must be at least a **5** in accordance with TU Delft's exam regulations. The assignments are **not required**, though they count towards the final grade.
- Assignments are done in **pairs of two students** and are graded by student assistants in a binary manner (pass or fail). There are five assignments in total, three cover Web programming topics and two cover database topics.
- There is one option to resit one or more of the Web programmign assignments in the week before Christmas.

## Course topics

- Week 1: (Lecture 1) HTTP and (L2) HTML5
- Week 2: (L3) JavaScript and (L4) node.js
- Week 3: (L5) CSS and (L6) node.js (advanced topics)
- Week 4: (L7) Cookies & sessions and (L8) Web security
- Week 5: DB topics
- Week 6: _no lectures_ this week; midterm on Thursday (*the midterm only covers Web programming topics*)
- Week 7: DB topics
- Week 8: DB topics
- Week 9: DB topics (still to be decided whether that week is lecture-free)

## Assignments

Across the five assignments, a Web application, using the modern Web stack will be built.

If you are new to team programming, and want to use VSC's features efficiently, [read our guide](How-to-use-VSC.md). While it is beyond the scope of this course to introduce tools like `git` in detail, we provide you with enough information to get started. You will learn more about these tools in later courses.

- [Assignment 1](Assignment-1.md)
- [Assignment 2](Assignment-2.md)
- [Assignment 3](Assignment-3.md)
- [Assignment 4](Assignment-4.md)
- [Assignment 5](Assignment-5.md)

## Interactive Web technology exercises

Students who do not have a lot of prior knowledge often struggle to get started.
Here is a [list of useful interactive exercises](nodeschool-exercises.md) and how they match up with each lecture. 

## Handing in your code

- proper `package.json`
- proper `README.md` (check provided template)
- Heroku deployment(?)

## List of Web lectures (2017/18)

- Lecture 1 ([PDF-1](https://chauff.github.io/documents/webdb-2017-18/web-http.pdf), [PDF-2](https://chauff.github.io/documents/webdb-2017-18/web-http-continued.pdf)) on **HTTP**: HTTP 1.1 request/response message, important HTTP headers, Web caches, HTTP methods, telnet, IP addresses
  - Required readings: *none*
  - Recommended readings:
    - Chapters 1, 2 and 3 of [HTTP: The Definite Guide (O'REILLY 2002)](http://shop.oreilly.com/product/9781565925090.do)
    - [MDN overview of HTTP](https://developer.mozilla.org/en-US/docs/Web/HTTP)
    - Read up on the developer tools of your favourite Web browser (e.g. [Firefox](https://developer.mozilla.org/son/docs/Tools) or [Chrome](https://developer.chrome.com/devtools))
    - [A brief history of HTTP](https://hpbn.co/brief-history-of-http/)
    - Note that http information can be used for [browser fingerprinting](https://arstechnica.com/security/2017/02/now-sites-can-fingerprint-you-online-even-when-you-use-multiple-browsers/)
  - Addition in 2018/19: `Keep-Alive` and `Update` (WebSockets) headers; [info](https://medium.com/platform-engineer/web-api-design-35df8167460); [tutorial](https://www.html5rocks.com/en/tutorials/websockets/basics/)
    - [A comic intro to http(s) and dns](https://hacks.mozilla.org/2018/05/a-cartoon-intro-to-dns-over-https/)
    - Include `Access-Control-Allow-Origin` header in the discussion
  
- Lecture 2 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-html5.pdf)) on **HTML5**: Web sites vs. Web applications, Electron, Web design basics (*Don't make me think* by Steve Krug), usability testing, HTML5 history, Web standards, HTML forms, AppCache
  - Required readings:
    - Chapter 2 of the [Web course book](http://shop.oreilly.com/product/0636920030621.do)
    - HTML form slides
  - Recommended readings:
    - Chapter 3 of the [Definite Guide to HTML5](https://www.apress.com/gp/book/9781430239604)
    - [From AppCache to Service Workers](https://developers.google.com/web/fundamentals/instant-and-offline/offline-cookbook/)
    - [Web Fundamentals by Google](https://developers.google.com/web/fundamentals/)
    - [Running Firefox headlessly and why](https://developer.mozilla.org/en-US/docs/Mozilla/Firefox/Headless_mode)
    - [Examples of what modern Web technologies can achieve in Chrome](https://experiments.withgoogle.com/) (if you use another browser, not all examples may work as expected)
    - [Progressive web apps](https://developer.mozilla.org/en-US/docs/Web/Apps/Progressive#Core_PWA_guides)
  
- Lecture 3 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-javascript.pdf)) on **JavaScript** (client-side): functions as first-class citizens, object creation, basic constructor, prototype-based constructor, module, WebConsole, scoping, events and the DOM
  - Required readings:
    - Chapter 4 of the [Web course book](http://shop.oreilly.com/product/0636920030621.do)
  - Recommended activities:
    - Follow the [CodeSchool Try jQuery](https://www.pluralsight.com/courses/code-school-try-jquery) course
    - Follow the [CodeCademy JavaScript](https://www.codecademy.com/learn/introduction-to-javascript) tutorial
  - Recommended readings:
    - [Learning JavaScript design patterns](https://addyosmani.com/resources/essentialjsdesignpatterns/book/), in particular the sections on the [constructor pattern](http://addyosmani.com/resources/essentialjsdesignpatterns/book/#constructorpatternjavascript) and the [module pattern](http://addyosmani.com/resources/essentialjsdesignpatterns/book/#modulepatternjavascript).
    - MDN's introduction to [JavaScript objects](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects)
    - [What the f*ck JavaScript](https://github.com/denysdovhan/wtfjs) - a list of funny and tricky JavaScript examples
    - [A blog post on why the dynamic nature of JavaScript makes optimization tricky](https://v8project.blogspot.com/2017/09/elements-kinds-in-v8.html)
    - A good blog post on [why we need all those fancy tools for JavaScript development nowadays](https://medium.com/the-node-js-collection/modern-javascript-explained-for-dinosaurs-f695e9747b70)
    - A very good podcast on [debugging](https://syntax.fm/show/047/how-to-get-better-at-debugging)
    - [Blog post about recent research on JavaScript libraries](https://blog.acolyer.org/2018/06/20/conflictjs-finding-and-understanding-conflicts-between-javascript-libraries/)
    - Stanford University teaches [Programming Methodologies in JavaScript](http://web.stanford.edu/class/cs106j/)
    - [Info on the `<script>` tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script)
    - [Check with Lighthouse](https://developers.google.com/web/tools/lighthouse/)
    - [Service Worker Cookbook](https://serviceworke.rs/)
    - [Learn how to debug with Firefox devtools](https://mozilladevelopers.github.io/playground/debugger)

- Lecture 4 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-nodejs.pdf)) on **node.js**: history, npm, event loop (single-threaded and highly parallel), watch a file for changes (`fs`), networking with node.js (`net`), web server creation (`http`), urls for routing (`url`), Express framework (`express`), JSON, Ajax
  - Required readings:
    - Chapters 5 & 6 of the [Web course book](http://shop.oreilly.com/product/0636920030621.do)
  - Recommended activities:
    - [learnyounode](https://github.com/workshopper/learnyounode) is an interactive tutorial of node.js
    - [how-to-npm](https://github.com/npm/how-to-npm) is an interactive tutorial on the use of npm (node's package manager)
    - CodeSchool has a [node.js module](https://www.codeschool.com/courses/real-time-web-with-node-js) tutorial as well; free trial available
  - Recommended readings:
    - A [comprehensive list of node.js resources](https://github.com/sergtitov/NodeJS-Learning) is updated by Sergey Titov
    - The recommended IDE for this course is [Visual Studio Code](https://code.visualstudio.com/) (open-source, available for all major operating systems). [Here](https://vscodecandothat.com/) is a good overview of some of the very useful but less obvious features of VS.
    - [Event loop explained](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
    - [Automated testing with node](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Cross_browser_testing/Automated_testing)
    - [Node.js stats of 2017](https://medium.com/the-node-js-collection/node-js-state-of-the-union-blog-2017-ed86640ec451)
    - [MDN Express tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website)
  
- Lecture 5 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-css3.pdf)) on **CSS**: history, CSS3, pseudo-elements (`first-letter`,`after`,`before`) and pseudo-classes (`nth-child`,`nth-of-type`, `first-child`, `hover`, `enabled`, `not`, `in-range`), rendering engine, `content` attribute (data in CSS), CSS counters, browser-specific prefixes, element positioning (`float`, `position`, `display`), CSS coordinate system, CSS media queries, CSS animations and transitions
  - Required readings:
    - Chapter 3 of the [Web course book](http://shop.oreilly.com/product/0636920030621.do)
  - Recommended activities:
    - Take a look at the ["pens"](https://codepen.io/pens/#) showcased at [CodePen.io](https://codepen.io/#); it is a good platform to see what is possible in front-end Web development
    - Watch [this YouTube video from CSSConf](https://www.youtube.com/watch?v=cYGOv2ToZjY) covering the long (and painful) history of CSS
  - Recommended readings
    - Chapters 1-4 and chapter 13 of [The Book of CSS3: A developer's guide to the future of Web design](https://nostarch.com/css3_2e) by Peter Gasston (2nd edition, 2014)
    - To make sense of CSS positioning, take a look [here](https://developer.mozilla.org/en-US/docs/Web/CSS/position_value) and [here](https://alistapart.com/article/css-positioning-101)
    - Blog post on Mozilla's [CSS engine Quantum CSS](https://hacks.mozilla.org/2017/08/inside-a-super-fast-css-engine-quantum-css-aka-stylo/)
    - [Animation.css](https://daneden.github.io/animate.css/)

- Lecture 6 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-nodejs-continued.pdf)) on **advanced node.js**: Ajax in more detail, node.js modules (`module.exports`, `require`), middleware, routing, regular expressions, templating with EJS
  - Required readings: *none*
  - Recommended activities:
    - An interactive ejs playground can be found [here](https://ionicabizau.github.io/ejs-playground/).
    - An interactive playground for express routes and regular expression is available [here](http://forbeslindesay.github.io/express-route-tester/).
  - Recommended readings:
    - To learn more about ejs, take a look at its [GitHub repository](https://github.com/mde/ejs).
    - To learn more about middleware and Express, take a look at the [Express documentation](http://expressjs.com/en/guide/using-middleware.html).
    - An overview of [best practices in node.js](https://github.com/i0natan/nodebestpractices)
    - [Slide deck on High Performance JS in V8](https://docs.google.com/presentation/d/1KCcA-WAyhGs0SEOrfU21fjaTWTxvNxYLwmNlGIbuZFw/edit?usp=sharing)
    - Blog post in best practices to create a [node package](https://monades.roperzh.com/bootstrapping-javascript-library/)

- Lecture 7 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-cookies-sessions.pdf)) on **cookies and sessions**: session vs persistent cookies, cookie fields, cookie flags/domain, cookies in Express (accessing and deleting them), evercookie, third-party cookies, client-side cookies (`document.cookie`), sessions in Express (memory stores), third-party authentication (OAuth 2.0, example authentication through Twitter via `passport`)
  - Required readings: *none*
  - Recommended activities: *none*
  - Recommended readings:
    - Chapter 9 of [Web Development with Node & Express](http://shop.oreilly.com/product/0636920032977.do) by Ethan Brown
    - Instead of cookies to recognize a user, we can also resort to the more stealthy version of [browser fingerprinting](https://arstechnica.com/security/2017/02/now-sites-can-fingerprint-you-online-even-when-you-use-multiple-browsers/)

- Lecture 8 ([PDF](https://chauff.github.io/documents/webdb-2017-18/web-security.pdf)) on **Web security**: Web application threats, attack due to a lack of data validation, OS command injection, SQL injection, broken session management, cross-site scripting (stored and reflected), insecure direct object references, security misconfiguration,  cross-site request forgery
  - Required readings: *none*
  - Recommended activities:
    - In a "star module" two years ago, two first-year students in TI1506 implemented [CrapStore](https://github.com/nielsdebruin/CrapStore), a node.js based Web app modeled after BadStore (discussed in class). Try it out if you want to test some basic Web security issues.
  - Recommended readings:
    - If you want to know everything there is about security, read Ross Anderson's [Security Engineering book](https://www.cl.cam.ac.uk/~rja14/book.html) (available for free). [Chapter 21](http://www.cl.cam.ac.uk/%7Erja14/Papers/SEv2-c21.pdf) is most pertinent to the Web security lecture (warning: this is an extensive read).
    - [Stanford's CS155](https://crypto.stanford.edu/cs155/): Computer and Network Security course has a number of lectures on Web security (PDFs: [here](https://crypto.stanford.edu/cs155/lectures/08-browser-sec-model.pdf), [here](https://crypto.stanford.edu/cs155/lectures/10-SessionMgmt.pdf), [here](https://crypto.stanford.edu/cs155/lectures/09-web-site-sec.pdf) and [here](https://crypto.stanford.edu/cs155/lectures/11-workers-sandbox-csp.pdf))
    - CERN's [Web security lecture](https://indico.cern.ch/event/242207/) contains a lot of the material covered in class
    - The [Open Web Application Security Project](https://www.owasp.org/index.php/Main_Page) (OWASP) provides an extensive list of practical tips, best practices and further readings on the topic.
    - [Node.js security best practices](https://medium.com/@nodepractices/were-under-attack-23-node-js-security-best-practices-e33c146cb87d)
    - [Deployment of the app on Heroku and securing it with Helmet](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/deployment)
    - [Scientific paper on tracking](https://securehomes.esat.kuleuven.be/~gacar/persistent/the_web_never_forgets.pdf)
    - [Capture the Flag](https://hacks.mozilla.org/2018/03/hands-on-web-security-capture-the-flag-with-owasp-juice-shop/)
    - [Who left open the Cookie Jar?](https://wholeftopenthecookiejar.eu/static/tpc-paper.pdf)
