---
layout: post
title:      "CLI Data Gem Portfolio Project"
date:       2020-03-19 18:45:02 +0000
permalink:  cli_data_gem_portfolio_project
---


This project was interesting; I have never built a web scraper before, and was working from a mis-assumption that they were complex and difficult. Instead, I found it to simply be extremely detail-oriented (which I am, so this aspect felt pretty natural). I basically started with the broadest scope - connecting to the website and storing the HTML - then worked my way down to more and more specific applications, testing repeatedly along the way. Since I utilized the website's built-in search feature, which returns multiple pages, I had to include functionality testing for the presence of the "Next Page" button. Final process, therefore, was: 1. Run website's search feature (url-driven) using the user-provided search term. 2. Scrape the page for the desired link types and store the data. 3. Check for the presence of the "Next Page" button. 4. If the button is present, load the next search results page. 5. Repeat steps 2. through 4. for each page with a "Next Page Button". 6. Ensure data from final search results page is stored. 7. Process all data into program-accesible formats (class instances and attributes). 8. Present data and choices of how to view it. Overall, I had quite a lot of fun with this.
