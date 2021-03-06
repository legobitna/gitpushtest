# Precourse Assignments: Hello World!  & Travel Blog

![](https://i.imgur.com/nuNQ55P.png =128x)




## Introduction and Background

Welcome to CoderSchool! It's really exciting to meet you. You're about to join a cool journey into programming, and the first thing you'll want to say is:

![](https://i.imgur.com/glRvr4y.gif =300x)

Every programmer starts with "Hello World", it's just [a computer programmer's tradition](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program). 

For this assignment, we're introducing Markdown, a very simple programming language. Markdown is just a very simple way to make **formatted text**. 

> With just a couple of extra characters, Markdown makes rich document formatting quick and beautiful.

## Assignment #1: Hello World!
For your first assignment, we'll ask you to publish a small page written in Markdown to the internet. Think of it as a mini homepage. Here's an example of what we'll ask you to build: [ Charles Lee's Hello World Page](https://gist.github.com/chug2k/db756b482d4e8a2dfe3500148ce2b582).

![Charles Screenshot](https://i.imgur.com/VEK6iM1.png)


CoderSchool is very assignment oriented, so we'll ask you to accomplish these first few steps. Feel free to have fun with this assignment and go more advanced if you'd like. 

Why this assignment? 
1. We want to introduce you to Markdown, which is a useful language for technical documentation used by every programmer.
2. We want to check that you can follow instructions.
3. We want to introduce you to how CoderSchool homework assignments are structured.
4. We want to get to know you better.


## What You Should Do

Create a site, similar to the screenshot above, on GitHub.com. We'll walk you through the basics below.

## Deadline

You **must** submit this assignment **within the next 3 days (72 hours)** to be eligible to join the course.

It should take less than 30 minutes to complete this assignment, so we highly encourage you to do it now. Like, right now, just keep reading and you can get this done right away.

## Assignment Requirements

**Required**
* [ ] Page published to a Github Gist.
* [ ] Top Level Header that includes your name
* [ ] Second Level Header called Basic Information, with a bulleted list about yourself.
* [ ] Information about your favorite movie, with a link to the movie's page on [TMDB](http://www.themoviedb.org). 
* [ ] At least two images.

**Bonus, Optional Things to Do**
* [ ] A table of information (*hint: link #3 in the Background Reading Section*)
* [ ] Images that link to a Youtube Video (*hint: link #4 in Background Reading*)
* [ ] Something to make the grader of your assignment laugh


## Instructions

### Step 1: Sign up for Github

[GitHub](www.github.com) is the most popular site on the internet for coders. We'll be using it a lot throughout the course, but today we'll just use one simple feature called gists. Go to GitHub.com and sign up for an account, using the big form.

![](https://i.imgur.com/CGLEiTw.png)

### Step 2: Go to Gists

Once you've logged in, go to [http://gist.github.com](http://gist.github.com) in your browser. Create a new file here.

![](https://i.imgur.com/FCi7tkq.png)

For description, call it "CoderSchool Prework". For the second field, call it `hello_world.md`. Don't forget the `.md` extension!

### Step 3: Create your gist

You can get started by simply typing:

```
# Hello World! 
```

Once you've done that, click the "Create Public Gist" button. It doesn't actually matter which button you press; create secret gist is also okay for this case.

![](https://i.imgur.com/S81rVBD.png)

After you verify that your "Hello World" is working, go back and click "Edit" to continue editing your gist until you've fulfilled all the requirements above. The edit button is hard to see, but it's in the upper right. 

![](https://i.imgur.com/J3jo6lZ.png)




## Assignment #2 : Travel Blog
For this assignment, you will create a travel blog (using HTML) about the cities that you have visited. You should have images of the cities, lists of things to see and places to go, and paragraphs of enticing details. 
You should also use CSS to style the website, using a mix of the simple selectors.

## Required features of your blog: (Creativity is encouraged!)
- Contains a Title (header)
- Contains at least 3 headings and 3 paragraphs. (how you get there, how you like them)
- Contains at least 2 lists. (for e.g: bullet points for famous food in those cities)
- Contains at least 3 images. 
- Contains at least 3 links (anchor tag) to websites about those cities (e.g Wikipedia?) 
- Uses at least 5 CSS id or class selector to change colors, size, align...of title, heading, paragraph, images
- Contains no syntax errors or bad practices, and your code should be formatted correctly.
- Make it as beautiful as you can.


## Milestone 1: 
  There are a couple of good websites out there offer online coding tool like Codepen, Replit, jsFiddle. Today we will use [Codepen.io](https://codepen.io/)
- First register your account at codepen
- Click on Start Coding, you should see a screen that looks like this:

![](https://i.ibb.co/F7jh2Bw/1-1.png)

  In this lab exercise, we only use basic HTML and CSS, so you can hide the JS box for more space on the screen.
- We can now start writing our first line of code.
- Please note that Codepen already simplifies the work for you. There are actually a few more codes running behind what you see on the screen.

## Milestone 2: add blog title, city: heading & paragraph
-  Before we start, you should spend a couple of minutes to skim through the [list of html elements here](https://www.w3schools.com/tags/default.asp) so that later on if you have any confusion you can refer to this page again.
-  To insert a title for our blog, we use the tag (element) `<h1> </h1>`. By default, this will be the biggest text in your html.
-  Now add heading and paragraphs for a city. Actually, a heading is just like a title with smaller size or less standout appearance. We will use  `<h2> </h2>` and `<p></p>` . By default `<h2>` text will be 1 level smaller than `<h1>` . I've visited in Lausanne, Switzerland. So let's start with adding the first city: Lausanne.
- There are also `<h3>` and up to `<h5>` so you can use them for sub-headings.
- After adding all the texts, your code should look similiar to this:

![](https://i.ibb.co/T0nMcrJ/2-1.png)

- Okay, let's add more thoughts on the city.

## Milestone 3: add images properly.
I really like this phrase: "A picture is worth a thousand words". Images will make our blog lively and attractive. Let's add a couple of images to our blog. 
- To add an image to html file, we normally use `<img>` tag: `<img src="path_to_image" alt="name_of_image" />`.  
- If you do it correctly, your blog should look like mine:

![](https://i.ibb.co/ysqZfRP/3-1.png)

- [Read more on `<img>` tag](https://www.w3schools.com/tags/tag_img.asp)

## Milestone 4: add lists and links
- To insert a list we could use:
  - `<ol></ol>` ordered list (you have have a list of 1. item, 2. item, 3. item for example) or 
  - `<ul></ul>` for unordered list (without the number but bullet points instead).
  -  Read more on this here [ul](https://www.w3schools.com/tags/tag_ul.asp),  [ol](https://www.w3schools.com/tags/tag_ol.asp)

- We use `<ul>  </ul>` to wrap all the list items `<li> list item  </li>`. 
- To insert a link, we use anchor tag `<a> Some text </a>` with a required attribute `href` (href="path_to_some_webpage"). There are a couple of optional attributes in `<a>` which are [explained here](https://www.w3schools.com/tags/tag_a.asp)

![](https://i.ibb.co/RHKPXwz/4-1.png)


## Milestone 5: Styling with CSS
We're going to give our blog some styling. But before that, we need to separate our html code into different blocks. In html we call it `<div>`. And then we give it a `class` or `id` to link that element with our specific attribute in CSS . This code below is the how you should write in acss file.
```
.css-rule-class {
    property1: value;
    property2: value;
}

#css-rule-ID {
    property1: value;
    property2: value;
}
```
Now let's start styling by writing some codes inside the CSS box. 

### **Styling with selector ID**:
**id is global attribute of html. It specifies a unique id for an element through out the whole html file.**
- First let's give an ID for our title and heading.
```
<h1 id="title">A Wanderer's Blog</h1>
<h2 id="city-heading">Peaceful Lausanne</h2>
```
- Then style them within our CSS. 
First we want our blog title to be in the center of the page, with a red color, and a bigger size -  so we style our id: title like below:
```
#title {
  text-align:center;
  color: red;
  size: 3rem;
}
```
- The heading for our city "Peaceful Lausanne" should be in green (I like green):
```
#city-heading {
  color: green;
}
```
- Notice that I used `rem` as unit? Instead of using `rem`, we can also use `px` or `em` . You can [read it here](https://engageinteractive.co.uk/blog/em-vs-rem-vs-px) to know more about when to use which of them

- Ok nice. Now our blog looks a bit better with some very basic styling. But our images don't look so nice. Some of them have different sizes. We need to style them too. Give `<img>` an id called `content-image` and style them like this:
```
#content-image {
  height: 400px;
  width: auto
}
```
  I use fixed height of 400 pixel for all images and not really care about the width

### **Styling with class**:
**Class is a global attribute. An element in html can have multiple classes**. We wrap each heading and paragraph inside a `div` element and give it a `class` called `mini-content`.Your html code should look like this:

![](https://i.ibb.co/dtZFT3r/5-1.png)

-  And we also want some space between our blocks (heading + paragraph). The styling for class should be like this:
```
.mini-content {
  padding-bottom: 1rem;
}
```

- One last thing, let's add some space on the left edge of the page to make it nicer. Wrap the whole html code we have written inside a `div` and give it a class called `content`. Then style it in CSS:
```
.content {
  margin-left: 2rem;
}
```

After all this, your blog should [look like this](https://i.ibb.co/9Y4ydmx/readme.gif) (or much better)

![readme.gif](https://i.ibb.co/9Y4ydmx/readme.gif)


## Milestone 6:
- Now add more cities and make it as beautiful as you can.




---


# Submit your assignments

Once you're done, go to [this page](https://forms.gle/6jCQCvNbW5zxYMwZ7)  to submit your homework. 

- The GitHub link to your Gist can be found in the address bar of the browser on the page you just created:

![](https://i.imgur.com/uLxBKMl.png)

- And the link to your codepen can also be found in the address bar of the browser that you were working with codepen.

![](https://i.ibb.co/NsrqFhg/Screen-Shot-2019-09-29-at-9-09-08-AM.png)


Congratulations! We'll probably see you in class if you read this far. 

## Background Reading

  1. [The ultimate guide to Markdown](https://blog.ghost.org/markdown/)
  2. [Markdown explained in Vietnamese](https://www.codehub.vn/Markdown-La-Gi)
  3. https://guides.github.com/features/mastering-markdown/
  4. https://stackoverflow.com/questions/11804820/embed-a-youtube-video
  5. [All of html elements](https://www.w3schools.com/tags/default.asp)
