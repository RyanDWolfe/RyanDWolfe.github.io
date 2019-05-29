---
layout: post
title:      "MVC Design"
date:       2019-05-29 20:05:04 +0000
permalink:  mvc_design
---


I find it super important to sketch out development ideas first so that you don't run into a bunch of iterations and changes to your models, views, and controllers. I have read a bit on best practices of what to include in each of the components of MVC's, but I wanted to document my own thoughts.

I tend to find myself free writing and drawing out ideas and then coming back and compartmentalizing them to fit a developer schema.

Generally speaking, thinking through the VIEW and how a user will interact with the software is the best place for me to start since that will ultimately dictate the functionality on the back end. I think this helps prevent trying to account for lots of edge cases in the MODEL that may never exist because of the constraints to the VIEW. Then if you make changes to the view, you can follow the logic to ensure your routes and models can handle it.

Then I like to switch over to the dababase and create the schema and table relationships which will dictate how the MODEL and CONTROLLER interact with it. Optimizing this part helps prevent rework on how you insert and retrive data in your application.

Then building the logic in the MODEL for how the application will actually run becomes so much easier as you know what form your data will be in to manipulate.

Finally, hooking everything up in the CONTROLLER and testing to make sure everythings works as intended.

This won't apply to every project, but I think it is a good appoach.


