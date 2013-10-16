tumblr
===

this is pretty far from complete at the moment, and you'll need to figure out how to get your oauth credentials from tumblr on your own for the moment

usage
---

* get-all-the-stuff.py -- run this one to download all your blogs, posts, likes, followers, and more all at once. This still needs some work
* get-blog-posts -- creates json objects in the data folder for each blog post for the blog you specify on the command line.
* get-blog-images -- downloads the high-res version of images for all your blog posts to the data folder.

dependencies
---

* [pytumblr](https://github.com/tumblr/pytumblr)
* oauth2
