# CHERI-Zephyr Project Website

## How to use locally
Managing Ruby / Jekyll dependencies can be really annoying.  To correct for that, we use a docker image rather than relying on whatever the latest version of ruby/jekyll are installed on your machine for building the site!  Tech is based on [this blog post](https://ryanharrison.co.uk/2026/02/22/building-jekyll-sites-with-docker.html).  You do not need to install ruby/jekyll locally; the container should handle everything.

To test the site live locally (with live reload) simply run the following command:
```
$ docker compose up
```

The site should then be live @ <http://localhost:4000>.   Once the site is running, feel free to edit any of the site's `.md` files and see the changes immediately updated in your browser.

## How to publish
TBD.  Might use <https://github.com/BretFisher/jekyll-serve> in some CI/CD workflow?  Look at how missing semester does this on push.

## TODO
* Add video of demonstrator
* Fix all FIXMEs in the `_config` file
* Deploy page publically
* Actually write real content for About page
