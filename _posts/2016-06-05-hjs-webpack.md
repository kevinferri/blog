---
layout: post
title: Quick Configuration for ES6 + React
---
Configuring a React app with ES6 can be a hassle.

Setting up webpack can be a bit painful, especially without having a previous template to follow. Not to worry, however! We’ll be building our webpack configuration with the help of a well-built webpack starter tool called hjs-webpack.

The hjs-webpack build tool sets up common loaders for both development and production environments, including hot reloading, minification, ES6 templates, etc.

Let’s grab a few webpack dependencies, including the hjs-webpack package:

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
