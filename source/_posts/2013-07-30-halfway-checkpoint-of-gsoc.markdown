---
layout: post
title: "Halfway Checkpoint of GSOC"
date: 2013-07-30 01:04
comments: true
categories: gsoc
---

Time passes really fast. The midterm evaluation starts. Good news is that everything goes on schedule. I just finished the server-side implementation of the XBRL reporting project as I planned in my proposal. Actually it was an unexpectedly busy summer. The school suggested us to finish a course during the summer and I need to pack my stuff and prepare for my move to Pittsburgh. The daily checkin kept me making progress every day even on a busy day.

My mentor KOJO introduced test-driven development to me, which not only makes the code strictly follow the requirement but also helps the developers to think more about the modularized and decoupled patterns when designing code structures. We paired with each other on writing unit tests and integrationtests. The test tool Mockito is one of the neat things I've learned when pairing with KOJO. Sometimes test code can be hard to write because of all the dependencies a class has. That is where Mockito comes in, mocking the unrelevent dependencies so that you can focus on the method you test.

Making good use of great open source building and managing tools is another secret to the make of a successful open source community. Mifos uses this fantastic tool Gradle to automate the building process. The convenience Gradle brought shocked me when I first built the mifosx server. And I knew more and more about its capability when getting a deeper look inside it. Other great tools like maven and flyway, even tomcat, that Mifos uses are integrated within gradle. It's really like an all-in-one package.

I am going to finish the client UI in the next half of gsoc. This means a switch from Java to less familiar Javascript. It is a challenge, but also a good oppportunity to learn about frontend developing.