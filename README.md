# Web-Scraping-Flipkart
Web scraping an online shopping site in India (Flipkart) using BeautifulSoup in python. 

Python is used because it has a wide range of libraries to use for webscraping like BeautifulSoup, scrapy, etc,.

Now, if you know regular expressions, you might be thinking that you can write code using regular expression which can do the same thing for you. I definitely had this question. In my experience with BeautifulSoup and Regular expressions to do same thing I found out:

->Code written in BeautifulSoup is usually more robust than the one written using regular expressions. Codes written with regular expressions need to be altered with any changes in pages. Even BeautifulSoup needs that in some cases, it is just that BeautifulSoup is relatively better.

->Regular expressions are much faster than BeautifulSoup, usually by a factor of 100 in giving the same outcome.

So, it boils down to speed vs. robustness of the code and there is no universal winner here. If the information you are looking for can be extracted with simple regex statements, you should go ahead and use them. For almost any complex work, I usually recommend BeautifulSoup more than regex.I've used BeautifulSoup here.

Enter product u want to search on flipkart as input.

All the products in search results on the webpage of flipkart will be printed along with price and rating.
Along with the output in the window, a file named "products.csv" will be created in the same folder as the program. It will contain the product name, price and rating of the each search result in a tabular manner.

I've attached products.csv file as an example for the search query "iphone" with this.

