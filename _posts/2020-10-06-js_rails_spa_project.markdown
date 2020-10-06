---
layout: post
title:      "JS Rails SPA Project"
date:       2020-10-06 06:56:50 +0000
permalink:  js_rails_spa_project
---


This project was extremely difficult. JavaScript can be finicky, and I ran into a roadblock with almost every step. In particular, I spent way too much time dealing with AJAX requests via fetch. I was trying for quite a while to wait for the requests to finish, then access the data. This would basically eliminate the asynchronous portion of using AJAX, which defeats the purpose. I ultimately came to the conclusion that I already had the data I wanted to access loaded into the page and stored either in object or in the values of the form, so I sent to requests to update the database, but did not wait for the return data to continue page operation.  This solved the issue.  I also ran into a lot of difficulty with time management on this project. Going forward, I will be paying much more attention to how much time is left throughout the entire process, and produce an MVP ASAP.
