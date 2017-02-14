# Bootstrap
Bootstrap is a popular front-end web framework created by Twitter developers.

## What's a "front-end"?
Web development is commonly distinguished into a "front-end" side and a "back-end" side. For example, take a website like Amazon. The front end is what you see and directly interact with when you visit www.amazon.com in a web browser. Front-end concerns include web design and usability testing. Currently, we have been mainly working on front-end development, using HTML and CSS. (JavaScript is also another language used in front-end development which we have not worked with yet.)

On the flip side, "back-end" development deals with what the user does not see, but is usually the most critical aspect of a web site or app. For example, back-end components of Amazon.com might include databases which store customer data, track orders, and so on. (I say "might" because since I do not work for Amazon, I do not know what their back-end looks like!) Common technologies and languages used in back-end development include (but are definitely not limited to) SQL, Python, PHP, Java, and so on. If web development were a restaurant, the dining area would be the front-end, and the kitchen would be the back-end.

## Using Bootstrap
Details of how to use Bootstrap will be covered in the meeting, but you should install the dependencies required so we can get moving quickly.

### Dependencies
Instructions adapted from: http://getbootstrap.com/getting-started/#grunt

#### 1. Install **node.js**
Go to https://nodejs.org/en/ and download and install the appropriate version for your OS.

#### 2. Install Grunt
Grunt is a node.js module used for compiling Bootstrap's CSS files. To install Grunt:

 1. Install ```grunt-cli``` globally with ```npm install -g grunt-cli```.
 2. **(Ignore this step for now)** Navigate to the root ```/bootstrap/``` directory, then run ```npm install```. npm will look at the package.json file and automatically install the necessary local dependencies listed there.

**If you run into errors, trying using the terminal/running cmd with admin privileges.** Otherwise, everything's good. See you at the meeting!
