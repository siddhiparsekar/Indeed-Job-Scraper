# Indeed Job Scraper
 A web scraper to extract job postings from www.indeed.com using Python. I have used Beatiful soup and the request mosule to scrape the data.

Module used:
bs4: Beautiful Soup(bs4) is a Python library for pulling data out of HTML and XML files. This module does not come built-in with Python. To install this type the below command in the terminal.
pip install bs4

requests: Request allows you to send HTTP/1.1 requests extremely easily. This module also does not come built-in with Python. To install this type the below command in the terminal.
pip install requests

Approach:
Import all the required modules.
Pass the URL in the getdata() function(User Defined Function) to that will request to a URL, it returns a response. We are using get method to retrieve information from the given server using a given URL.


