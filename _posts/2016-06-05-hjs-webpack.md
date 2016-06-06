---
layout: post
title: Quick Configuration for ES6 + React
---

{% highlight js %}
var getConfig = require('hjs-webpack');

var config = getConfig({
  in: 'src/app.js',
  out: 'build',
  clearBeforeBuild: true
});

module.exports = config;
{% endhighlight %}
