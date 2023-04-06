---
title: "BuildContext: From Confusion to Capstone"
date: 2023-04-05T14:57:21-07:00
# lastmod: 2023-04-05T14:57:21-07:00
draft: false
keywords: []
description: ""
tags: []
categories: [Capstone]
author: ""

# Uncomment to pin article to front page
# weight: 1
# You can also close(false) or open(true) something for this content.
# P.S. comment can only be closed
comment: false
toc: false
autoCollapseToc: false
# You can also define another contentCopyright. e.g. contentCopyright: "This is another copyright."
contentCopyright: false
reward: false
mathjax: false

# Uncomment to add to the homepage's dropdown menu; weight = order of article
# menu:
#   main:
#     parent: "docs"
#     weight: 1

# Image source: https://pixabay.com/vectors/confusion-left-right-straight-311388/
---
![Image of person on questionable path.](/image/confusion.png)

Maybe everybody feels like they didn't get the manual, but that feeling has always been especially visceral for me. I'm a child of two immigrants from two different countries. And I grew up in a country where nobody spoke the language, including my parents. Culture shock with a side of confusion was served up with my morning breakfast cereal. *What was right and what was wrong? What was inappropriate? What was normal?* These things were already hotly contested within my household so, the special sauce of the outside world did not add any clarity. It is also very important to add, without offering the full transparency of my birth year, that I grew up without the internet. Looking something up involved either an already dated encyclopedia or a trip to the school library. FYI - doom scrolling used to occur within the bounds of the dewey decimal system.

Flash forward through college. I graduated with a degree in my native language and with job prospects everywhere (as long as they included extensive training as part of the onboarding process). Somehow the slingshot of growing up propelled me right past waiting for my life to start to already living it without any kind of.. *dare I say it?* ... plan. Most jobs chafed. I knew I was capable of more but often found myself in menial supportive roles, working tirelessly to further somebody else’s career. After a few false starts, I decided to work for myself as… *drumroll, please…* an artist. I traded in a low salary for a menial 40 hour a week job for an even lower pay rate working 70+ hours a week.

> I learned so much more as a self-employed artist than I ever did in college.
>

Being an artist was not a plan as much as it was a leap into a different life: a life where I was in charge. I couldn’t be right or wrong because I was making it up as I was going along. (I started to have an unnerving suspicion that the rest of the world was operating in a similar fashion.) I learned so much more as a self-employed artist than I ever did in college. I found my customer base. I pitched my work. I changed my work when it wasn’t well-received. I navigated budgets, sales, marketing, website construction, social media, hotel bookings, art show applications, photographs and… *right,* making art. I started to make plans. Many plans. Plans with backup plans and contingency plans. Plans with short-term goals and long-term goals. Plans that nested short-term wins within long-term gains. How did I not know about this before? Planning is awesome. **Life is so much better with a plan.**

About 10 years passed. COVID was the great disruptor for a lot of lives, and it was no different for me. My work ground to a halt and I found myself with something I rarely experienced: free time. ***Free, unpaid time.*** The combination held promise but also a quiet desperation to accomplish something. I tried on and discarded hat after hat. Side hustles. New hustles. Business ideas and career shifts grabbed my attention and were just as quickly dismissed. I found myself back in the old familiar trap. The work I could get chafed. I could do better, but I couldn’t get better. I needed to start over. I was back at square one, but I was back at square one with the internet.

[CS50](https://pll.harvard.edu/course/cs50-introduction-computer-science?delta=0) changed everything for me. I had never taken a [MOOC](https://en.wikipedia.org/wiki/Massive_open_online_course) before and I had no idea that such high quality educational materials existed online *for free.* It was just another hat at first. I didn’t know what programming was. I thought that at the very least it would exercise my brain and keep me from staring at the wall. It was hard, but more importantly… ***it was fun.*** It was so much fun that I didn’t want to leave my desk. The problems were different than anything I had ever worked on before but they were also familiar. They were problems that teased the part of my brain that liked to fix things: the part of my brain that liked to build things and to plan.

I was enrolled in the [OSU post-bacc program](https://ecampus.oregonstate.edu/online-degrees/undergraduate/computer-science-postbacc/) and taking my first CS classes within 6 months of completing Harvard’s CS50. I was so proud. I lived in an [OSU College of Engineering t-shirt](https://osubeaverstore.com/osu-college-of-engineering-tee-w-seal-black.html) I bought at the Beaver Store. I mocked up a Swift iPhone app. It was just a big red button that displayed, **“I’m an Engineer!”** when pressed. I studied and worked hard. It was harder than my first degree, but nowhere near as hard as being self-employed. How did I not know that I was supposed to be an engineer? ***Why didn’t anyone ever tell me that there was a career path filled with nothing but ideas and documentation?***  


![Image of a Flutter Widget build method.](/image/flutter_code.png)  


18 months later I was in my next to last term with a 4.0 GPA and my first elective courses. One of them was Mobile Development, which is taught in the Dart programming language using the [Flutter SDK](https://flutter.dev/). I had thought about apps before but never tried to do more than a basic execution. I had more on my resume than the big red button, but the Mobile Development class was a deeper dive. I wasn’t sure how I felt about Dart at first. Its class structure reminded me of Java, which I loved, but it also had arrow functions like Javascript which is… *Javascript*. I want to say it was around week 3 or 4 of the 11 week term that I was reading about a Flutter application being constructed of a tree of widgets.  **Yep, sure.** And how every widget has a build method. **Good, good, makes sense.** And every build method is passed one thing. **OK.** And that one thing is… *context.* **Can I be a widget, please?**

Less than 3 months later I’m taking my last two classes before graduation and one of them is the Capstone project. I’ve accepted an offer as a SDE at AWS and rationally I know that I should be working on a cloud based project. Despite this, I find myself in the completely unique position of getting to build exactly what I want to build for a very targeted customer base: me (i.e. women). I pitched the idea to work solo on a mobile app that I want to build and take to market and I was given permission to do it. 
So what has changed? I’ve been building things my whole life. Why does this feel different? I’m an engineer just starting out in her career. I have a new relationship with a very responsive SDK that says all the right things. I have a job waiting for me that doesn’t offer trivial pay. I have a plan for what I want to do and where I want to go. And, perhaps most importantly, I have plenty of detailed documentation. (I’m pretty sure the documentation makes all the difference.) 

