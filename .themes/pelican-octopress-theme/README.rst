Octopress Theme for Pelican
===========================

This is a theme for `Pelican`_ that looks like `Octopress`_ default theme. I wrote this
theme for `my personal blog`_.

Why use this theme?
-------------------

I really like Octopress default theme, I think is enough pretty and very readable. On the other
hand I don't like any of the themes currently available for Pelican. As I'm not able to write a
nice theme from scratch I've just copied the Octopress' one.

Why didn't you use Octopress?
-----------------------------

I've started writing my blog with Octopress but I haven't found a way to easily have a
multi-language blog without hacking more than the time I was planning to spend to setup my blog.
You can argue that the time spent to copy the Octopress' theme is more than adding a
multi-language feature for Octopress.. I'm not sure of that since I've no idea what kind of
changes Octopress required to support multiple language per post.

I've found out that I like more the organization of Pelican: Octopress/Jekyll have a unique
repository you have to fork, so its code is mixed with your blog's data. Pelican instead separates
the two things. Also Pelican is written in Python that I know way better than Ruby.

The theme is missing `XXX`
--------------------------

I've started writing this theme just for my blog and my blog required few template pages and few
features. If you want to add `XXX` please be free to fork this repository and submit a pull request,
I'll be happy to merge it!

Plugins
-------

This theme add a nice section on the sidebar with a list of GitHub repositories of the user.
You can enable it by using these settings:

- ``GITHUB_USER``: (required to enable) your username
- ``GITHUB_REPO_COUNT``: ``5``
- ``GITHUB_SKIP_FORK``: ``False``
- ``GITHUB_SHOW_USER_LINK``: ``False``

This theme also allows sharing via Twitter, Google Plus, and Facebook.  To
enable any of these, use the following settings:

- ``TWITTER_USER``: (required to enable) your username
- ``GOOGLE_PLUS_ID``: (required to enable) your ID
- ``FACEBOOK_LIKE``: (required to enable) ``True``

Extra Twitter options (default values are shown):

- ``TWITTER_WIDGET_ID``: (required to enable feed) ID obtained from `twitter settings <https://twitter.com/settings/widgets>`_
- ``TWITTER_TWEET_BUTTON``: ``False`` show twitter tweet button
- ``TWITTER_FOLLOW_BUTTON``: ``False`` show twitter follow button
- ``TWITTER_TWEET_COUNT``: ``3`` number of latest tweets to show
- ``TWITTER_SHOW_REPLIES``: ``'false'`` whether to list replies among latest tweets
- ``TWITTER_SHOW_FOLLOWER_COUNT``: ``'true'`` show number of followers

Extra google plus options (default values are shown):

- ``GOOGLE_PLUS_ONE``: ``False`` show +1 button
- ``GOOGLE_PLUS_HIDDEN``: ``False`` hide the google plus sidebar link.

Google Analytics
-------------

- ``GOOGLE_ANALYTICS``: "UA-XXXX-YYYY" to activate Google Analytics(classic)
- ``GOOGLE_UNIVERSAL_ANALYTICS``: "UA-XXXX-Y" to activate Google Universal Analytics
- ``GOOGLE_UNIVERSAL_ANALYTICS_COOKIEDOMAIN``: ``'auto'`` optional cookie domain setting for Google Universal Analytics
- ``GOOGLE_ANALYTICS_DISPLAY_FEATURES``: ``True`` to enable `Display Advertiser Features <https://support.google.com/analytics/answer/2444872?hl=en&utm_id=ad>`_. This setting works for both Classic Analytics and Universal Analytics.

Sidebar image
-------------

- ``SIDEBAR_IMAGE``: Adds specified image to sidebar. Example value: "images/author_photo.jpg"
- ``SIDEBAR_IMAGE_ALT``: Alternative text for sidebar image
- ``SIDEBAR_IMAGE_WIDTH``: Width of sidebar image

- ``SEARCH_BOX``: set to true to enable site search box
- ``SITESEARCH``: [default: 'http://google.com/search'] search engine to which
  search form should be pointed (optional)
  
QR Code generation
-------------

- ``QR_CODE``: set to true to enable the qr code generation for articles and pages by browser

FeedBurner integration
----------------------

- ``FEED_FEEDBURNER``: set this to the part of your FeedBurner URL after the ``http://feeds.feedburner.com/`` to set the
  displayed feed URL to your FeedBurner URL. This also disables generation of the RSS and ATOM tags, regardless of whether
  you've set the ``FEED_RSS`` or ``FEED_ATOM`` variables. This way, you can arbitrarily set your generated feed URL while
  presenting your FeedBurner URL to your users.

X min read
----------

medium.com like "X min read" feature. You need to activate the plugin
``post_stats`` for this to work (default values are shown):

- ``X_MIN_READ``: ``False``

Favicon
-------

- ``FAVICON_FILENAME``: set to path of your favicon. The default is empty in
  which case the template will use the hardcoded address ``favicon.png``.

Contribute
----------

#. Fork `the repository`_ on Github
#. Send a pull request


Authors
-------

- `Maurizio Sambati`_: Initial porting of the theme.
- `Geoffrey Leh??e`_: GitHub plugin, some cleaning and some missing standard Pelican features (social plugins and links).
- `Ekin Erta??`_: Open links in other window, add tags and categories.
- `Jake Vanderplas`_: Work on Twitter, Google plus, Facebook, and Disqus plugins.
- `Nicholas Terwoord`_: Additional fixes for Twitter, Google plus, and site search
- `Mortada Mehyar`_: Display advertising features for Google Analytics
- ... and many others. `Check the contributors`_. 


.. _`Pelican`: http://getpelican.com
.. _`Octopress`: http://octopress.org
.. _`my personal blog`: http://blogs.skicelab.com/maurizio/
.. _`the repository`: http://github.com/duilio/pelican-octopress-theme
.. _`Maurizio Sambati`: https://github.com/duilio
.. _`Geoffrey Leh??e`: https://github.com/socketubs
.. _`Ekin Erta??`: https://github.com/ekinertac
.. _`Jake Vanderplas`: https://github.com/jakevdp
.. _`Nicholas Terwoord`: https://github.com/nt3rp
.. _`Mortada Mehyar`: https://github.com/mortada
.. _`Check the contributors`: https://github.com/duilio/pelican-octopress-theme/graphs/contributors
