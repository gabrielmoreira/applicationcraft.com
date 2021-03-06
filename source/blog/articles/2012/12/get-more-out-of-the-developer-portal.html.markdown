---
title: Get more out of the Developer Portal
author: Ian Jobling
tags: support, portal, bugs
date: 2012-12-18
class_name: blog
full_width: true
---

As much as we all hate bugs and problems, they happen, and it's also nice to see a lot of you reporting problems in our <a href="http://portal.applicationcraft.com" target="_blank">Developer Portal</a>. 

I thought I'd throw out a few tips to help you out, and explain the basics of what we do with your tickets. We've already made a few tweaks from comments that have been made, so if you have any thoughts/ideas don't be shy - we'd love to hear from you.

## Raising a problem ##

Complete all the fields! Not only the platform (eg iOS/Android) but also what OS is involved. 

Attach an app which we can import into our test accounts and quickly and easily recreate the problem. Don't forget to also include a 'step by step' of what to do in your app so we know what to do.

An example or test app is even better. An export of your app (the .acft file) is preferred and not a download (.zip file) or compiled package.

If you can't export your app then show us the problem in a video. The old adage: 'A picture is worth a thousand words' really is true. Screen shots can also be helpful. It may seem counter intuitive but even if your problem is only experienced on a mobile device, and you can't easily video that, being able to walk through how to recreate the problem from the desktop app to show the steps can be a lot easier than trying to write it down step by step. <a href="http://www.techsmith.com/jing" target="_blank">Jing</a> is very good for doing this. Give it a go next time you have a problem, and simply post the link to the screencast in your ticket.

If you can do the above it will help speed up the time it takes us to recreate the problem and get it fixed.

## What have we released and when? ##

We've added in a new field to the ticket *Planned for Ver* that is being set with the version we plan to release the fix for. 

I've set up some **Custom Queries** that you can use to see what was released in past versions. As we release new updates I'll create new queries as we do  (eg 1.28.1, 1.28.2) and as we release a new version (eg 1.29, 1.30). I will then combine all the updates into one query (eg 1.26.x, 1.27.x).

![Send](/img/blog/queries.png "Custom Queries")

You can set up your own queries on demand but if you have ones that you would like to be publically available, let me know and I'll sort something out for you.

## Ticket Status ##

When a new issue is raised, it is given the status of 'New'. But what happens next and when are you then able to test/check that we've sorted out the problem?

You can test the fix when the status changes to *Deployed/Released* as that is when the fix is released.  

![Send](/img/blog/ticketwf.png "Ticket Workflow")

Between these 2 steps, there are a number of process steps. If your explanation isn't clear we may get back to you changing the status to *To Clarify*, but in most cases (and especially if you include an example app) the next step would be to set the status to *Acknowledged* for the developers to pick up. 

Watch out for the change to the *Planned for Ver* flag to indicate what version this is due to be released in. This will be done when our QA team have tested internally and passed it as OK to release. In most cases this will be the next release we make, but if there are other things we need to do (update the docs for example), it may be different.

## Keep it Clean ##

When you have confirmed all is OK, please add a comment to the ticket to let us know and we can then close it out.

## Private Posts ##

If you raised your ticket as a Private post (ie includes information you would not want to have in the public domain, export of an app, screen shots, etc.), we would like to make these Public when they have been closed, so others can also see if they have or had a similar problem.  Please delete any attachments/comments that you wanted private and then un-check the private flag as you confirm back all is Ok for us to close the ticket and the rest of the community can then see what happened.



