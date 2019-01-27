---
layout: post
title:  "Opengraph?"
date:   2019-01-27 08:55:42 -0600
categories: jekyll update
comments: true
---
+ What is Open Graph and how do you make use of it?

Opengraph makes a preview of your website when you share it, on socialmedia for example.

I just added different meta tags in head.html.  
Tested on facebook.

### Example
This is the meta tag for setting the preview image whe i share my blog on social media.  
{% highlight html %}
<meta property="og:image" content="http://ogp.me/logo.png" />
{% endhighlight %}