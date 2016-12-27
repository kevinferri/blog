---
layout: post
title: First Post
---

This is a test for a post

{% highlight bash%}
npm install --save-dev hjs-webpack webpack
{% endhighlight %}

{% highlight js %}
var getConfig = require('hjs-webpack');

var config = getConfig({
  in: 'src/app.js',
  out: 'build',
  clearBeforeBuild: true
});

module.exports = config;
{% endhighlight %}
