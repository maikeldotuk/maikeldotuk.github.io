---
title: The server code - Part 3 Refactoring and TMA02
layout: post
categories:
- theproject
date: 2018-04-02 00:00:00 +0000
---
![](/uploads/2018/04/02/Capture.PNG)

I've started by creating a git init for the backend as I didn't notice I didn't have it version controlled.

But now that is finished and I'm going to refactor the whole thing and clean it up for the TMA it must be version controlled.

### One day later

I haven't only refactored but I have also added documentation of the entire API. Using a tool called apidocs which was incredibly easy to learn. I will use it again for my own site in www.maikel.uk

Now the backend is finished and deployed in

[https://www.maikel.uk/project/](https://www.maikel.uk/project/ "https://www.maikel.uk/project/")

The result is in the image above this post which I will probably use for TMA02. Which I'm going to start writing now.

It took me just 3 hours to get all the documentation written and the backend deployed on my website.

### To take in consideration

1. The Apache configuration, I've changed it manually, this should be reflected on the site. This means the AMI needs re-doing. 
2. The environment variables need to be declared. Check serverconf.json
3. The file serverconf.json needs to be created, it has private keys and the salt for the tokens, is either that or download it with the AMI. 