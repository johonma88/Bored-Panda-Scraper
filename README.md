# Bored-Panda-Scraper


### Overview

The Bored Panda Scraper is a scraper app which captures the title, summary and image of articles of The Bored Panda Website. In this app, users are able to save their preferred articles, add notes and edit notes to one or multiple articles. Besides, app also provides search feature, allowing users to search in titles according to different key words.

See the Magic, please go to Heroku:



### Key Dependencies

`request`: enables `cheerio` to get access to front-end code of https://www.boredpanda.com/category/animals/?show=trending

`cheerio`: scrapes front-end code from https://www.boredpanda.com/category/animals/?show=trending

`mongoose`: be in charge of database of `Bored_Panda`

`express`: builds server-side routes and functions

`morgan`: logs server-side requests, helping debugging

`express-handlebars`: a powerful front-end builder without requiring multiple html pages
