# INT303-web-scraping
A coursework of big data analysis

Data is scraped from: https://maoyan.com/board/4
Overall structure of data scraping:
Get all ranking pages contents as soup;
Get all movie links from ranking pages as a list;
Get all movie pages from links as soup;
Save ranking pages and movie pages as .txt for further collection;
Collect demanded data.
Attention: The anti-spider of this website is strong and I deal with this with user-agents and ip proxies. However, smooth and repeated access is not guaranteed. If the outputs keep saying 'attemp again', please refresh the web page and complete the verification on the url (or href of movie, actors, directors and so on) manually if demanded.

Author: Yeheng Ma 1822070
