# bleacher_scraper

I wanted to be able to get daily fantasy news in my inbox every day. This was I didn't have to go to an external site (in this case Bleacher Report) and sift through their site to find what I cared about. I used Inspect to identify the sections I cared about and Beautfiul Soup to actually scrape these sections. Then I used SMTP to send the information scraped to my email. And set up a cron job to do this every day.

For more info on setting up cron jobs, check out this site: https://plainenglish.io/blog/auto-schedule-python-scripts-on-mac-37adac5db520
