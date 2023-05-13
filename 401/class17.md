# Web Scraping

## Reading Questions

* What are the key differences between scraping static and dynamic websites?
  * Static websites load all the information all at once within the HTML file itself.
  * Dynamic websites update their data depending upon what is needed at that particular time. The data is typically in the Javascript files which can make scraping more difficult.

* Explain at least three techniques or best practices that can be emplayed to avoid getting blocked while scraping websites.
  * Follow the rules for scraping that particular site which is typically called robot.txt
  * Throttle the scraping such that it's not slamming the site with requests
  * Randomize the crawling pattern
  * Use a headless browser like Playwrite

* What is Playwrite, and how does it assist in web scraping tasks? Provide an example of a use case where Playwrite would be particularly beneficial.
  * Playwrite is a library with tool specifically made for web scraping. In the case of dynamic websites it's able to navigate through and will have a higher chance of extracting the required information.

* Describe the purpose of using Xpath in web scraping, and provide an exmaple of an Xpath expression to select a specific HTML element from a webpage.
  * It allows specific elements to be targeted in terms of web scraping.

## Readings and Media

* [Scrape a Dynamic Website with Python](https://scrapingant.com/blog/scrape-dynamic-website-with-python)
* [What is Web Scraping?](https://en.wikipedia.org/wiki/Web_scraping)
* [How to scrape websites without getting blocked](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)
* [Login and Scrape Data with Playwright and Python](https://www.youtube.com/watch?v=H2-5ecFwHHQ&t=60s)
* [Python Playwright Tutorial For Beginners](https://www.youtube.com/watch?v=yp1o9biMMWU)
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/)
* [Playwright XPath Selectors](https://www.programsbuzz.com/article/playwright-xpath-selectors)
* [Xpath Cheatsheet](https://devhints.io/xpath)
* [Render Dynamic Pages - Web Scraping Product Links with Python](https://www.youtube.com/watch?v=MeBU-4Xs2RU)
* [Rendering Dynamic Pages 2! - Web Scraping ALL products with Python](https://www.youtube.com/watch?v=B14mtXA7Tyw)
* [Selecting an element containing certain text](https://stackoverflow.com/questions/1520429/is-there-a-css-selector-for-elements-containing-certain-text)