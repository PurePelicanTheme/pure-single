Pure Single
===========

[Blogging theme](http://purepelican.com) based on [Purecss](http:purecss.io) for [Pelican](http://docs.getpelican.com/) blogs.
Theme is responsive.

## PELICANCONF.PY

* `COVER_IMG_URL` - Set the sidebar image (Optional).
* `PROFILE_IMG_URL` - Set the image for the top circle cutout.
* `TAGLINE` - Used for the page titles and some meta tags.
* `FAVICON_URL` - Set the favicon image
* `DISQUS_SITENAME` - Set this to enable disqus comments in articles.
* `DISQUS_ON_PAGES` - Set this to True to enable disqus comments in pages.
* `GOOGLE_ANALYTICS` - Set the Google Analytics code (eg. "UA-000000-00")
* `PIWIK_URL` and `PIWIK_SITE_ID` - Set the URL and site-id for Piwik tracking. (Without 'http://')
* `SOCIAL` - Set some social links in the sidebar. The format should be like this:

    ```python
    SOCIAL = (
        ('github', 'https://github.com/example/'),
        ('twitter-square', 'https://twitter.com/example'),
    )
    ```
    where the first value of the tuple is the icon name from http://fontawesome.io/icons/ after stripping `fa-` (eg. `fa-github` will be `github`)

## Custom article metadata:
* `sidebarimage` - will replace the image on the sidebar on an article basis

## Aditional features
* [FitVids](https://github.com/davatron5000/FitVids.js) jQuery plugin for fluid width video embeds.


