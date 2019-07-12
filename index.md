---
layout: default
title: "Oleg Silkin"
description: "This is a culmination of all the things I've worked on"
---

## Education

<div id='framingham-state'/>
##### [**Framingham State University,** *Framingham, MA*](https://www.framingham.edu/)  
<div id='framingham-state-math'/>
***B.S. Mathematics***    
*Degree Anticipated: May 2020*  
> Concentrated on topics related to Quantitative Analysis such as Abstract Algebra, Graph Theory, and Analysis. Spent a lot of time researching the application of Abstract Algebra to create a flexible framework for arbitrary computational models.

<div id='framingham-state-cs'/>
***B.S. Computer Science***  
*Degree Anticipated: May 2020*  
> Studied the Relational Database model, as well as its mathematical basis in Relational Algebra. Learned how to properly design and implement normalized relational databases in various Database Management Systems.



<div id='harper-college'/>
##### [**Harper College,** *Palatine, IL*](https://www.harpercollege.edu/index.php)  
<div id='harper-college-degree'/>
***Associates of Engineering***    
*August 2016 - May 2018*  
> Focused on learning fundamental topics in Mathematics such as Linear Algebra and Multivariate Calculus that help provide a foundation to many subjects in Computer Science as well as other applied mathematics.  


## Experience


##### Full Stack Developer - [***LBRY Inc.***](https://github.com/lbryio)  
*January 2019 - Current*  
> Developed user comment system, and integrated into an existing blockchain stack to promote user engagement and increase product value (see [LBRY-Comments](#lbry-comments) for more details). Enforced proper logical-layer schema independence to create the framework to ensure a clean transition when hot-swapping product components.


## Projects

<div id='lbry-comments'/>
##### [LBRY Comments](https://github.com/lbryio/comment-server/README.md)
> Created a RESTful comment system from the ground up and integrated it with the rest of the blockchain stack. [Created a server](https://github.com/lbryio/comment-server/README.md) with `aiohttp` and `SQLite` to store and retrieve user data. Then provided functionality in the [lbry-sdk](https://github.com/lbryio/lbry-sdk) to  act as a front-facing API for the server. Designed UI layout for user comments into [lbry-desktop](https://github.com/lbryio/lbry-desktop) using `React` + `Redux`.

<div id='skipsort'/>
##### [SkipSort - O(n) Probabilistic Sorting Algorithm](https://github.com/osilkin98/skipsort)
> Created sorting algorithm with `O(n)` time-complexity for data sets where `|n| < n`,   
where `|n|` represents the number of unique entries.
This was accomplished by using a skiplist with a modified height probability factor `p` such that `p^k = n` with `k = log_p(n)`,
where `1 <= k < log_2(n)`.  This allows us to have a worst-case complexity of `Θ(n*log_p(n))` and an average complexity of `O(n)`.


##### [DogeAI — Image Classifier Deployed as a Twitter Bot](https://github.com/osilkin98/DogeAI)
> Created an image classifier which recognizes images of the Doge Meme
and allows users to send in images and interact with them according to
what they sent in.
Additional modifications were made for guaranteed uptime which takes
into account sudden shutdowns, network connectivity, etc.

##### [HappyMail — User Adjustable Sentiment Filter](https://github.com/osilkin98/HappyMail)
> Made an app using the Gmail API which sifts through a user’s inbox and
learns which letters the user doesn't want to see. For instance if you don't want to get contacted about random job offers from recruiters, you can just mark them as being unwanted, and the algorithm will learn to filter out any similar letters.


## Skills & Other Misc. Stuff
***TODO***
