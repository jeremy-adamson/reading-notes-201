# Reading 01

Updated 10/15/22

## Getting Started

When making a site, keep in mind:

* What will the website be about?
* What information is to be presented on the subject?
* What will the site graphically look like?

Note to call a script

* \<script src="scripts/main.js"></script>

### Terms

* TCP/IP - communication protocols that define how data should travel across the internet
* DNS - Domain Name System is like an address book for websites (gets the IP)
* HTTP - Hypertext Transfer Protocol defines a language for clients and servers to speak to each other
* Component files
  * Code files - the actual code (HTML, CSS, JS, etc)
  * Assets - Non-code portions of the site such as images, music, video, etc.

### **Assignment**

* Compose a short poem describing how HTTP sends data between computers
  * I have no clue how to put it into a poem but the way I understand it is HTTP would be the words written on a card/letter and the TCP/IP is the stamped envelope
* Describe how HTML, CSS, and JS files are "parsed" in the browser
  * The browser scans an HTML file for any CSS links or scripts
  * The browser then requests the needed CSS/JS files
  * Creation of a DOM tree occurs
  * Build of the DOM tree occurs incorporating the CSSOM tree along with excuting any JS
* How can you find images to add to a Website?
  * Google search BUT make sure that they are in the public domain
* How do you create a String vs a Number in JavaScript?
  * Both are similar by using the 'Let' statement but the type is only defined upon assignment
* What is a variable and why are they imporatant in JavaScript?
  * A variable can contain a stored value that can be accessed or changed (if not const) at a later time

## Introduction to HTML

### **Assignment**

* What is an HTML attribute?
  * "Provides additional information about HTML elements" [source](https://www.w3schools.com/html/html_attributes.asp)
* Describe the Anatomy of an HTML element.
  * An HTML element contains an opening tag (which might include an attribute with its value), content, and a closing tag
* What is the difference bewteen the article and section element tags?
  * An article is for a section of self-contained information/content while a non-article section depends on the rest of the site for context
* What elements does a "typical" website include?
  * html
  * head
  * meta
  * title
  * body
* How does metadata influence Search Engine Optimization?
  * It used to be the fields that seach engines would look for but apparently no longer due to spammers abusing this and filling the metadata fields with nonsense.
* How is the meta HTML tag used when specifying metadata?
  * the meta tag comes in two separate parts
    * name
    * content

## Misc

### **Assignment**

How to start to design a website:

* What is the first step to designing a website?
  * Asking the following questions
    * What exactly is to be accomplished
    * How will the site help get there
    * What will be the procedure to getting there
* What is the most important question to answer when designing a website?
  * Determining what you want to accomplish, what is the purpose of the site.

Semantics:

* Why should you use an h1 element over a span element to display a top level heading?
  * By definition h1 is what anyone would use for a top level heading.  That's what h1 means.
  * span could make something look like a h1 heading but... it's not a heading
* What are the benefits of using sematic tags in our HTML?
  * Tags with meaning are just that and that's literally part of the language.  The expected language helps search engines identify what's important, it helps with other code that's looking to interact with the extisting code, CSS, having other devs decipher what you've written, etc.

What is JavaScript?

* Describe 2 things that require JavaScript in the browser?
  * Interactive maps and music
* How can you add JavaScript to an HTML document?
  * Two ways
    * Internal - \<script>\</script>
    * External - \<script src = "" defer>\</script>

## Things I want to know more about

DOM trees

## Sources

[Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/) </p>
[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)</p>
[Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)</p>
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)</p>
[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/)</p>
[Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)</p>
[HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)</p>
[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)</p>
[How to start to design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)</p>
[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)</p>
[What is JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)</p>

