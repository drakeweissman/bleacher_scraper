# bleacher_scraper

<img width="1027" alt="image" src="https://user-images.githubusercontent.com/70959890/198293844-cb206f83-a615-45a2-87a4-bf893d24690b.png">

I wanted to be able to get daily fantasy news in my inbox every day. This was I wouldn't have to remember to go to an external site (in this case Bleacher Report) and sift through their site to find what I cared about. 

I identified the sections I care about on the site and used Inspect to find how they were nested in the HTML code. I then used Beautfiul Soup to actually scrape these sections programatically. Then I used SMTP to send the information scraped to my email. And set up a cron job to do this every day.

For more info on setting up cron jobs, check out this site: https://plainenglish.io/blog/auto-schedule-python-scripts-on-mac-37adac5db520
