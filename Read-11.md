# Audio, Video, Images

## IMAGES
Controlling the size and alignment of our images using CSS keeps rules that affect the presentation of our page in the CSS and out of the HTML markup.

We can control the size of an image using the width and height properties in CSS.

Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.

Basic Images Control:
You can control images through in-line styling, or using id and class through external CSS file.

Size of images syntax:

  img {
  width: 100px;
  hight: auto;
  }
Aligning images syntax:

  img {
  display: block;
  float: right;
  margin-left: 150px;
  margin-right: 200px;
  width: 40%;
  }
Centering images syntax:

  img {
  display: block;
  margin-left: auto;
  margin-right: auto;
  }
  
  ## Chapter 19: 

#### Practical Information : 

we are going to learn at some practical information that will 
help you launch a successful site.


Search Engine Optimization (SEO):



The Basics :

Search engine optimization (or 
SEO) is the practice of trying 
to help your site appear nearer 
the top of search engine results 
when people look for the topics 
that your website covers.



On-Page Techniques: 

On-page techniques are the 
methods you can use on your 
web pages to improve their 
rating in search engines.


Off-Page Techniques :

Getting other sites to link to you 
is just as important as on-page 
techniques. Search engines help 
determine how to rank your 
site by looking at the number of 
other sites that link to yours.



Hoe To Identify KeyWords And Pharses:


Determining which keywords to use on your site can be one of the 
hardest tasks when you start to think about SEO. Here are six steps that 
will help you identify the right keywords and phrases for your site.


1- Brainstorm

List down the words that 
someone might type into 
Google to find your site. Be sure 
to include the various topics, 
products or services your site is 
about.


2- Organize

Group the keywords into 
separate lists for the different 
sections or categories of your 
website.

3- Research

There are several tools that let 
you enter your keywords and 
then they will suggest additional 
keywords


4- Compare

It is very unlikely that your 
site will appear at the top of 
the search results for every 
keyword. This is especially true 
for topics where there is a lot 
of competition.


5- Refine

Now you need to pick which 
keywords you will focus on. 
These should always be the ones 
that are most relevant to each 
section of your site.

6- Map

Now that you have a refined list 
of keywords, you know which 
have the most competition, and 
which ones are most relevant, 
it is time to start picking which 
keywords you will use for each 
page


## Analytics: Learning about your Visitors

* Signing Up
The Google Analytics service relies on you signing up for an account at:
www.google.com/analytics The site will give you a piece of
tracking code which you need to put on every page of your site.

* How it Works
Every time someone loads a page of your site, the tracking code sends data to the Google
servers where it is stored. Google then provides a webbased
interface that allows you to see how visitors use your site.

* The Tracking Code
A tracking code is provided by Google Analytics for each website you are tracking. It
should appear just before the closing < /head> tag. The code does not alter the appearance of your web pages.


## How Many People Are Coming to Your Site?

The overview page gives you a snapshot of the key information you are
likely to want to know. In particular, it tells you how many people are
coming to your site.

*Visits*
This is the number of times people have come to your site. If someone is inactive on your site
for 30 minutes and then looks at another page on your site, it will be counted as a new visit.

*Unique Visits*
This is the total number of people who have visited your site
over the specified period. The number of unique visits will be lower than the number of visits
if people have been returning to your site more than once in the defined period.

*Page Views*
The total number of pages all visitors have viewed on your site. 

*Pages per Visit*
The average number of pages each visitor has looked at on your site per visit.

*Average Time on Site*
 he average amount of time each user has spent on the site per visit.

*Date Selector*
Using the date selector in the top right hand corner of the site, you can change the period of time
the reports display. When you log in, this is usually set to the last month, but you can change
it to report on a specific time period.

*Export*
The export link just above the title that says "visitors overview" allows you to export the
statistics on this page for other applications such as Excel.


FTP programs allow you to transfer files from your local computer to your web server.
Many companies provide platforms for blogging, email newsletters, e-commerce and other popular website
tools (to save you writing them from scratch).


## Audio and video elements
I think we've taught you enough in this article. The HTMLMediaElement API makes a wealth of functionality available for creating simple video and audio players, and that's only the tip of the iceberg. See the "See also" section below for links to more complex and interesting functionality.

Here are some suggestions for ways you could enhance the existing example we've built up:

The time display currently breaks if the video is an hour long or more (well, it won't display hours; just minutes and seconds). Can you figure out how to change the example to make it display hours?

Because < audio> elements have the same HTMLMediaElement functionality available to them, you could easily get this player to work for an < audio> element too. Try doing so.

Can you work out a way to turn the timer inner < div> element into a true seek bar/scrobbler â€” i.e., when you click somewhere on the bar, it jumps to that relative position in the video playback? As a hint, you can find out the X and Y values of the element's left/right and top/bottom sides via the getBoundingClientRect() method, and you can find the coordinates of a mouse click via the event object of the click event, called on the Document object. 
