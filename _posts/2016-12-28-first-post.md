---
layout: post
title: Test Post
---

This is a test for a post. I plan on writing posts/tutorials here in the future. For now, this post is just a placeholder.

In the meantime, feel free to check out my [resume](/resume).

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
