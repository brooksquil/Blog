Personal blog page

Setup

These commands are a helpful quick start. You may choose to ignore them completely and create your own directory structure. If you choose to use this recommendation, just copy the commands below. It doesn't matter what directory you are currently in.

mkdir -p ~/workspace/exercises/the-static-web/blog && cd $_
touch index.html
Requirements

Build a basic blog page that has 5 articles and any random topics you want to talk about. The text can be anything, even placeholder text ( look at this lorem ipsum text generator for an example of the official unofficial gibberish of web developers everywhere ).

There should be a page header containing the blog's title.
There should be a page footer containing the copyright notice. View pretty much any web site to see an example.
Each article has a header containing a title.
Each article has a footer containing the author and publication date.
Each article has at least one section.


# Blog Two

Blog Part 2

Prerequisites

⚠️ This exercise requires that you have completed the Blog Part 1 exercise.
Setup

Create a branch in your blog repository named version-2, and switch to that branch. git checkout -b version-2 will create and switch you into that branch.
This project is made up of several parts. By creating a branch for each section you will be able to preserve the concepts you have learned and able to reference them in the future. We have mentioned you should be commenting your code, right?
Requirements

Time to make Your blog into a single page application. Before you begin please review the sample code about building a simple SPA. At this point you should have a minimum of 3 personal blog posts.

Part One

In the navigation bar, make sure you have two links labeled "Blog List", and "Add Blog Entry".
Add a DOM element that contains input fields for the user to create a title, date, author, blog entry and keywords. You do not need to enclose them in a <form> element because we're not actually submitting this form anywhere.
Add a <button> element at the bottom of the input fields labeled "Add".
The input fields and the add button make up the Add Blog Entry View.
The existing view - all the blog entries - will be referred to as the Blog List View.
The Add Blog Entry View should not appear when the user first visits your page. Only the blog list should be visible.
When the user clicks on "Add Blog Entry" in the navigation bar, the Blog List View should be hidden, and the Add Blog Entry View should be shown (see example wireframe).
When the user clicks on "Blog List" in the navigation bar, the Add Blog Entry View should be hidden, and the Blog List View should be shown (see example wireframe).
Once the user fills out the blog entry form and clicks the add button, you should collect the values from the input fields, add the blog post to the array of blog objects, and update the blog list in the DOM.
Part Two

Create a JSON file for your blog entries.
Read from local JSON file with an XHR.
Loop over results and inject into Blog List View.
Add delete button to each blog entry and, when it is clicked, delete the entire entry in the DOM.