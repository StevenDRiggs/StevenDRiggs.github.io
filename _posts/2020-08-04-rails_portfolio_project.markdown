---
layout: post
title:      "Rails Portfolio Project"
date:       2020-08-04 09:42:53 +0000
permalink:  rails_portfolio_project
---


This project was a bear. It is HUGE, and I do not know how to build a small app even when the requirements have been small (see my Sinatra app for an example). I definitely learned a lot, though. I was able to abstract almost all of the code into the ApplicationController and helper methods, both of which brought similar issues. When using inheritance (as in the ApplicationController), you still have to be aware of which class is calling the method. For example, #index needs to know whether to load Author.all, Book.all or Genre.all. The before_action helped me tremendously here; I was able to run a pre-method for each route, setting instance variables identifying the calling class or object and performing some preprocessing to make it easier to work with. I did a similar thing in the helper methods, but quickly found out that the calling class in a helper method is a temporary, dynamically created class for the view. This changed how I had to write the code, and to solve it I used many 'self.send's. Overall, I really enjoyed stretching myself on this project, and look forward to the next one. 
