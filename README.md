Requirements
=============

- node.js 5.9.1 or above

Installation
=============

Install dependencies:
	npm install

Run application:
	./hackernews --posts n

*n* is number of posts you want to see in output

Run tests:
	npm test

Libraries used
=============
- bluebird is for Promises
- cheerio is for jQuery-like parsing of HTML


Output format
=============
	[
        {
            "title": "Web Scraping in 2016",
            "uri": "https://franciskim.co/2016/08/24/dont-need-no-stinking-api-web-scraping-2016-beyond/",
            "author": "franciskim",
            "points": 133,
            "comments": 80,
            "rank": 1
        },
        {
            "title": "Instapaper is joining Pinterest",
            "uri": "http://blog.instapaper.com/post/149374303661",
            "author": "ropiku",
            "points": 182,
            "comments": 99,
            "rank": 2
        }
    ]