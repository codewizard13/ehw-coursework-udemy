<!-- 🔗 Custom Stylesheet -->
<link rel="stylesheet" href="../../_css/main.css">


<!-- 🖼️ Site Logo -->
![Site Logo](/_pix/logos/logo-ehw-kb-h32.png)



<!-- 📝 Title -->
# 📒 COURSE NOTES: <span class="course-title">[The Ultimate React Course 2025: React, Next.js, Redux & More](https://www.udemy.com/course/the-ultimate-react-course/?couponCode=MT251107G2)</span>


## 📂 Section 03: **A First Look at React**


* **Section URL:** https://www.udemy.com/course/the-ultimate-react-course/learn/lecture/37350384#overview


<!-- 🧭 Navigation -->
### [🏚️ README](../../README.md) | [📁 Index](index.md) | [🔖 Bookmark](#bookmark)


<br>


**In this Folder:**



<section class="ehw-doc-descr">


These are my personal notes on **Section 3: A First Look at React** ...


</section>



<!-- 🏷️ RELATED TAGS -->
<section id="sec-tags">


## 🏷️ Tags:


- React
- JSX
- Components
- Props
- State
- Functional Components
- useState Hook
- Virtual DOM


</section>


---


<!-- 📖 TOC (Table of Content) -->
<details open>


<summary>Table of Contents</summary>


- [📒 COURSE NOTES: The Ultimate React Course 2025: React, Next.js, Redux \& More](#-course-notes-the-ultimate-react-course-2025-react-nextjs-redux--more)
  - [📂 Section 03: **A First Look at React**](#-section-03-a-first-look-at-react)
    - [🏚️ README | 📁 Index | 🔖 Bookmark](#️-readme---index---bookmark)
  - [🏷️ Tags:](#️-tags)
  - [▶️ VID 9:  Why Do Front-End Frameworks Exist?](#️-vid-9--why-do-front-end-frameworks-exist)
    - [Problems using Vanilla JavaScript to Build Front-End Applications](#problems-using-vanilla-javascript-to-build-front-end-applications)
      - [Problems with JS jQuery](#problems-with-js-jquery)
  - [▶️ VID 10: React vs. Vanilla JavaScript](#️-vid-10-react-vs-vanilla-javascript)



</details>
<!-- Lesson Notes -->

***

## ▶️ VID 9:  Why Do Front-End Frameworks Exist?

**Server-Side Rendering**

- Before 2010-ish, all websites were always rendered on the server
- Webiste is assmbled on the backend based on data and templates
- Resulting HTML/CSS/JavaScript then sends to website browser
- Browser then paints the site on the screen
- Ex: **WordPress**

- JavaScript used to only add simple animations, hover effects, etc.
- jQuery grew popular because it made JS work the same in all browsers
- Over time, devs wrote more and more JS code to be executed by the browser, which led to the rise of SPA (single-page applications)
- SPA: Webpages rendered on the client, not on the server

**Client-Side Rendering**

- Rendering the webpage shifted from server to the client
- These websites are called **web applications**
  
- web applications usually get data not from database, but from API
- app consumes api data and renders a screen for each view of the application
- feel like native desktop / phone app
- can click links / submit forms without the page ever reloading
- you are always on the same page, hence the name single page app


**NOTE:** Server side rendering is slowly getting popular again driven by **NextJS**, **Remix**, etc.


### Problems using Vanilla JavaScript to Build Front-End Applications


- Building front end applications receive data, changes the data as the user uses the app, always displays current data on the screen
- Most important task of any web application: ensure UI always displays **current state** of the data

**#GOTCHA:** Ensure state synchronization is a really hard problem to solve!


- **EX:** AirBnB

- Without a framework it would be super-hard to keep the data in-sync


#### Problems with JS jQuery


- Building a complex frontend with vanilla JS alone requires a large amount of direct DOM traversing and manipulation (class toggling, etc.)

- Results in entangled compex **"spaghetti code**

- Data is usually stored in the DOM (in hidden fields) shared across entire app; hard to reason, bugs


- Hard to understand and will introduce many bugs into the application

- If you try to solve the problems on your own you'll just end up creating your own framework, one way inferior to established frameworks like React.

- JS front-end frameworks exist because: keeping front-end interterfaces in-sync with data is really hard and a lot of work

- Front-end frameworks (like Angular, React, Vue) solve this problem so devs can focus only on the data and building user interfaces

- Frameworks enforce a correct way of structuring and writing code


## ▶️ VID 10: React vs. Vanilla JavaScript

- To get an first-feeling for how react keeps UI in sync with state, we compare the advice app fro the 1st sec with a vanilla JS implementation of the same application
















































