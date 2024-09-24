Assignment 2
Total marks: 100

Deliverables
A PDF report submitted to Canvas.

The PDF file must include student-name | SFSU-ID | Assignment 2 | your-GitHub-ID in the header section.
The body of your PDF report must contain a hyperlink to the GitHub repo of your answers to this assignment.
The body of your PDF report must contain the URL to your GitHub Pages deployed website.
Your Repo Structure
It is required for your repo to have the following file structure.

assignment-2-repo 
  ├─ index.html - # Entry point for your website must be named index.html
  ├─ views/  
  │  ├─ two.html 
  │  └─ three.html
  ├─ README.md  - # Include references to any articles on MDN or elsewhere that you used for this assignment.
  ├─ .gitignore - # Include any file/directory names that need not be tracked such as test, .vscode, etc.
  └─ resources/ 
     ├─ favicon.svg - # favicon used in your project
     └─ Everything else... - # All your SVG image files that you create will be in in this directory
Warning

For this assignment, any submission—where the report and/or the structure of the GitHub repo are not prepared according to the abovementioned instructions—will be graded with a maximum grade of 80.

Instructions
index.html
General Info
This files is the entry point to your website. To use GitHub Pages, this file needs to exist at the root of your repo. If it is not present, GitHub Pages will not deploy your website. It is vital that you verify that these requirements are met for a successful deployment.

Required features:
A custom banner image created by you using basic SVG elements.

Please refer to this document for a complete list of resources to help you with the SVG part of this assignment.

The banner width must be the full width of the screen.
The banner height is at 300px.
The banner image must at the top of the page.
The banner image must, at least, include one of each of the following elements:
<circle>
<rect>
<polygone>
Important

You have two options to add your SVG drawings to your html files:

using SVG code directly within <body></body> element.
using <img /> element to reference a SVG image file located in the resources/ folder.
More info is found on MDN.

<nav class="menue"></nav> element following the banner image.
This element contains an <ul></ul> element that contains list items that are each a hyperlink to the home page(./index.html), page two(./views/two.html) and page three(./views/three.html) of your website. More info and examples can be found here.
<h1></h1> element containing the following text: Assignment 2. This element is right after the nav element.
<h2 class="css-question"></h2> element containing the following text: How to Apply CSS to HTML. This element is placed right after the h1 element.
<p class="css-question"></p> element containing information on how to include an external CSS file in an html file with an example. This element follows the h2 element above.
Any code used in your answer is required to be enclosed within <code></code> or <pre></pre> elements. This MDN article explains how to apply external CSS to html.
<h2 class="js-question"></h2> element containing the following text: How to Use JavaScript in a Webpage. This element is placed right after the above <p></p> element.
<p class="js-question"></p> that follows the above h2 element. This paragraph element contains the following information:
How to link to an external JavaScript file with an example.
How to write JavaScript code within an html file with an example.
As mentioned earlier, any code used in your answers must be within a <code></code> or <pre></pre> elements.
This MDN article explains how to import JS code into a webpage.
Note

You are not asked to use any software to create SVG artwork. However, you are allowed to do so. For a list of tools to create SVG art, please click here

two.html
General Info
On this page, you are asked to create a table using HTML <table></table> element. The content of this table is your top three coding resources that you have found very useful in your computer science journey. These resources can be of any media: social media channels, books, blogs, websites, Discord channels, etc.

You may find this MDN article very useful for this part of the assignment.

If you happen to have no favorite coding resource, find some for this assignment, please.

Required features:
A custom banner page at the top of the page with the same requirements specified for the banner image in the previous secion.
You are allowed to use the same banner page that you created for index.html webpage.
Also, you are allowed to create another custom banner page, if you want to create more art!
Please, keep in mind that it is required that all banner images be of the same width and height on all pages of this website.
<nav></nav> element with the same specifications as in index.html.
<h1></h1> element with the following text: Favorite Coding Resources.
<table></table> element with four rows and two columns and a <caption></caption>. The first row is the heading of this table. Hint: you need to use <thead></thead> element to create a table heading row.
In short, for this basic HTML table, you are required to use <table></table>, <caption></caption>,<thead></thead>, <th></th> <tbody></tbody>,<tr></tr>, <td></td> elements.
For reference, the following is an example of a table with three rows. You need to create a table with four rows!

Coding Resource	Link
Mozilla Developer Network	https://developer.mozilla.org/en-US/docs/Web
DigitalOcean Tutorials	https://www.digitalocean.com/community/tutorials
three.html
General Info
On this page, you are required to create an SVG animation using <animateMotion></animateMotion>.

This SVG animation needs to be a seperate file named page-three.svg.

Hint: You will need <path></path> and <circle></circle> elements too. You are encouraged to view the code of a sample SVG animation file in this directory.

Required features:
A custom banner page as explained in the previous secion.
<nav></nav> element with the same specifications as in index.html.
<h1></h1> element with the following text: SVG Animation is easy!
<img></img>element referencing the SVG file of the animation that you have created:
The animation that you will create is of a small red circle traversing a perimeter of a square. More info can be found here
The animation needs to be a seperate file named page-three.svg and located in the \resources\ folder of your final repo.
The following is a reference graphic for this part of the assignment.


Optional feature:
You are encouraged to include a personal SVG artwork after the required animation on this page.
The top three SVG artwork, chosen by the instructor, will be featured on CSC317-04 main Canvas page for the entirety of March 2024.
favicon.svg
General Info
Per MDN:

A favicon (favorite icon) is a tiny icon included along with a website, which is displayed in places like the browser's address bar, page tabs and bookmarks menu. It is a usually a high-contrast image. There are free tools to create a favicon.

For a long time, SVG files could not be used as favicons since it was not supported by web browsers. However, it is now widely supported by different browsers. You are asked to create a high-contrast (e.g., black & white) favicon.svg file in this part of the assignment using your own drawings or any tool.

To include the favicon.svg in your website, you need to include the following in the of each of your html files:

<link rel="icon" href="path-to-your-favicon.svg" type="image/svg+xml">

Don't forget to update the relative path to your favicon.svg in the above code snippet.

A few helpful resources on favicon:

SVG, Favicons, and All the Fun Things We Can Do With Them
Bilding an adaptive favicon
Deployment
I did a demo during Feb.22 session on how to deploy a repo of a static website on GitHub to the internet using GitHub Pages.

A detailed guide with graphics can be found on GitHub Docs.

Some Tips about this Assignment
You are welcome to go about doing this assignment in whichever way you'd like to. But, here are some general tips:

As in any multi-part project, break the project into the most essential parts and start with them.
After setting up the skeleton of the project (aka scaffolding), start working on the required detailes for each page.
For example:

Create a local project folder on your local computer that matches the file tree structure that is mentioned at the top of this file.
The files you are creating in the step above should only be empty file but with the required file-name.suffix and directory names.
Then, initiate a Git repo in your local project directory to track the needed files.
Connect the local project directory to a remote repo on GitHub.com. This process is explained in detail in Feb.15.slides.pdf on Canvas.
After successfully setting up your remote repo, it is now time to get to code the required features of each page of this website.
You should first do all that is not SVG related. The reason I suggest that is because the SVG parts may take more time to finish.
Anything that is not SVG related is much easier to finish. For example, adding a heading(<h1></h1>) or a paragraph (<p></p>) element to a webpage can be done in less than a 1 minute!
Finally, make a habit of commiting your progress with meaningful messages (git commit -m "concise-message") and pushing it to your repo as often as you make progress with this assignment.
Ask your questions in the discord channel for this assignment with clear explanations and any relevant code or error message. Questions that lack clarity or supporting code are not fun to answer for anyone! Happy Coding!
