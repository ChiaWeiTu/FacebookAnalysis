# FacebookAnalysis
Facebook group members with Social network analysis-Python

purpose
Use python to write an automated program to capture the activity records of each group member in the Facebook Cypress snowboarding ride shared community within one month, including: the number of posts, the number of comments, and the number of emojis answered. Try to know who have more participation in the group. If there is a request want to go snowboarding with the shared ride, it is more convenient way to reach to the cypress mountain resort. 


Capture who and when from the posts, messages, and emoji replies in the community. If the time is within this month, keep this record, and finally count the participation of each person.


For the emoji part, I have to go to another tab to see those people who responded to this article or message at that time.

After clicking on the emoji, another small window will open, showing one by one what emoji the people responded to. We can also save the hyperlink here and go directly to the browser.



Steps:
1.Use selenium to log in to Facebook and go to the target club.
2.Operate selenium to scroll the page continuously. (The page of Facebook must be pulled down continuously, the old content will be displayed)
3.Operation selenium will view other X messages, OOO has replied, XX will reply, etc., open one by one.
4.Save the html source code of the current page.
5.Use beautifulsoup, re and other packages to parse the source code, and capture who posted and messages when.
6.If a post or message is within one month, the hyperlink of the reply emoji will be additionally stored.
7.Use selenium to go to the hyperlinks of the emoji one by one and record all the members in it.
8.Consolidate all the information and output the community meals and status of each member during this time.




