---
layout: default
title: "My Resume"
description: ""
---

## Education

### [**Framingham State University,** *Massachusetts*](https://www.framingham.edu/)  

#### ***B.S. Mathematics***  
*May 2020*  
> I'm currently broadening my horizons and studying as many different and unique
areas in Mathematics as I can. My interest is mostly in Mathematical Analysis,
however I've found abstract algebra to be incredibly fascinating & applicable
in ways I didn't even know were possible.


#### ***B.S. Computer Science***  
*May 2020*  
> I spent a lot of time being fascinated by relational databases and their
usefulness in data analysis. The methods acquired from abstract algebra had
also allowed me to form a deeper understanding of the relational model, and its
basis in set theory.




### [**Harper College,** *Palatine, IL*](https://www.harpercollege.edu/index.php)  
#### ***Associates of Engineering***    
 *August 2016 - May 2018*  
> Focused on jamming as many math classes into my schedule as humanly possible.
Outside of classes, I spent a lot of time receiving guidance from [Professor James][1]
on my Genetic Algorithm project, as well as various research problems I've
been working on.  




## Experience


### Volunteer Full Stack Development - [***LBRY Inc.***](https://github.com/lbryio)  
*September 2018 - Current*  
> Developed user comment system, and integrated into an existing blockchain stack to promote user engagement and increase product value (see [LBRY-Comments](#lbry-comments) for more details). Enforced proper logical-layer schema independence to create the framework to ensure a clean transition when hot-swapping product components.


## Projects


### [LBRY Comments](https://github.com/lbryio/comment-server/README.md)
> Created a RESTful comment system from the ground up and integrated it with the rest of the blockchain stack. [Created a server](https://github.com/lbryio/comment-server/README.md) with `aiohttp` and `SQLite` to store and retrieve user data. Then provided functionality in the [lbry-sdk](https://github.com/lbryio/lbry-sdk) to  act as a front-facing API for the server. Designed UI layout for user comments into [lbry-desktop](https://github.com/lbryio/lbry-desktop) using `React` + `Redux`.




### [SkipSort - O(n) Probabilistic Sorting Algorithm](https://github.com/osilkin98/skipsort)
> Created sorting algorithm with `O(n)` time-complexity for data sets where `|n| < n`,   
where `|n|` represents the number of unique entries.
This was accomplished by using a skiplist with a modified height probability factor `p` such that `p^k = n` with `k = log_p(n)`,
where `1 <= k < log_2(n)`.  This allows us to have a worst-case complexity of `Θ(n*log_p(n))` and an average complexity of `O(n)`.



### [DogeAI — Image Classifier Deployed as a Twitter Bot](https://github.com/osilkin98/DogeAI)
> Created an image classifier which recognizes images of the Doge Meme
and allows users to send in images and interact with them according to
what they sent in.
Additional modifications were made for guaranteed uptime which takes
into account sudden shutdowns, network connectivity, etc.

### [HappyMail — User Adjustable Sentiment Filter](https://github.com/osilkin98/HappyMail)
> Made an app using the Gmail API which sifts through a user’s inbox and
learns which letters the user doesn't want to see. For instance if you don't want to get contacted about random job offers from recruiters, you can just mark them as being unwanted, and the algorithm will learn to filter out any similar letters.


## Skills & Other Misc. Stuff
***TODO***


[1]: http://www2.harpercollege.edu/mathdept/james.html
