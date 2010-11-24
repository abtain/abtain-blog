Simple Rails Blog
=================

By Dan Quellhorst (dan@abtain.com)

This is the minimum viable blog. Comments are not currently supported.
Code is being used from the HTML5Boilerplate project.

Deploying
---------

Step 1: Signup for [Heroku](http://www.heroku.com/)

Step 2: Customize config/settings.yml

Step 3: Configure Heroku

    $ sudo gem install heroku
    $ heroku create myblog

Step 4: Deploy

    $ git push heroku master

Step 5: Visit your site
    [http://myblog.heroku.com](http://myblog.heroku.com)
