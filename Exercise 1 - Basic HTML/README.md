# What is HTML?
Do the readings and exercises to familiarize yourself with HTML concepts and syntax. The last exercise offers you the chance to use your newfound skills.

## Part 1: The Basics of HTML
Reading: https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started

### Did you get it?
Here are some questions to test your understanding of the article

 * What is an closing (ending) tag?
  * Do all tags need an ending tag?
  * Should every opening tag be paired with a closing tag?
 * What does it mean to "nest" an element?
 * Give an example of a block element
 * What is the difference between a block element and an inline element?
 * How do you add comments to an HTML document?

## Part 2: Adding text to pages
### How to mark-up text
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals

### How to make hyperlinks
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks

### More text mark-up options
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting

## Part 3: Practice
Here comes the fun part... creating an HTML document from scratch!

1. Start with a bare-minimum HTML document
This is the bare-minimum amount of code that comprises a valid HTML file.

 * Either use the one provided by Mozilla when you read "Creating hyperlinks" or…
 * Use http://vincela.com/html/#basics (just the section that says "A Bare-Minimum HTML Document")
  * Download 'bare_minimum.html'

2. Mark up this letter
https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter

 * Use the W3C validator mentioned: https://validator.w3.org/
  * Try to see if you can get your code to pass!

### Some Hints
#### Line Breaks
You should never use a line break to separate paragraphs. The correct way to create separate paragraphs is to wrap the paragraphs in ```<p></p>``` tags. The line break will then be created automatically.

If you want to create a line break within a paragraph, or any other element, use ```<br />```.

#### Styling
1. Copy and paste the CSS into a separate file. Save it in the same directory as "letter.css"
2. Add <link href="letter.css" rel="stylesheet" type="text/css"> to the <head> section of your HTML document
3. Any time you want to make any text right-aligned, you will set the container element's class attribute to "receiver-column", e.g.
 1. ```<p class="receiver-column">```
 2. Note: You might need multiple ```<p>```'s and ```<address>```'s to mark up the header!

#### A quick reference of most of the HTML tags you will need
http://vincela.com/html/ - Everything from the beginning up until the section "Fonts"
