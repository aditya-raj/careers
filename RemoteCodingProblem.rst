=====================
Remote Coding Problem
=====================

Build a working blog site
-------------------------

Your task, should you choose to accept, is to build a simple blogging site using Python, Django, PostgreSQL, and Apache. You will need to checkin your code to Github, so we can pull down the final result and run it locally. This means the entire codebase and any configuration files should be checked in. The following conditions must be met:

- create a public github repository and checkin your code there
- the blog should be written using Django 1.3.x & Python (2.6 or 2.7)
- the database powering your blog should be PostgreSQL
- site should be served via Apache and WSGI
- server configuration, should be included in the github repo

	- include https://github.com/votizen/careers/blob/master/.gitignore/ in the root of your repo

- the blog should allow multple users to log in to add/edit/delete articles
- staff users can write blog articles
- all site visitors can comment on blog articles (login not necessary)
- a blog article consists of a three parts: title, body, slug, and date
- POST requests for creating and updating articles and comments should process the request using Django forms and a view that you write. Do not use the Django admin for this.
- the title of each blog article should link to an article page, with the URL /{URL_SLUG_FOR_POST}/, not /posts/{POST_ID}/. This can be tricky to setup.

Extra credit
------------

Completing any of the following, in addition to the tasks above, will not only make your blog cooler, but also impress us:

- run your software on a public webserver
- pagination on the index page
- AJAX form submission
- any caching to reduce DB lookups
- support comment threading
- support thumbnails for users
- add a user profile and URL so users can edit
- fancy CSS


Feel free to email if you find any of this ambiguous.
