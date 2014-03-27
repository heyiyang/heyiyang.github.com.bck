---
layout: post
title:  "Ubuntu13.10 下安装 ruby2.0"
tags: [Ubuntu, Linux, Ruby]
---

在 Ubuntu13.10 的终端下执行以下命令安装 ruby2.0

{% highlight bash %}
sudo apt-get update
sudo apt-get install ruby2.0 ruby2.0-dev build-essential libssl-dev zlib1g-dev ruby-switch
{% endhighlight %}

将 ruby2.0 设置为默认值

{% highlight bash %}
sudo ruby-switch --set ruby2.0
{% endhighlight %}

安装并设置默认值后，执行以下命令查询 ruby 的版本

{% highlight bash %}
ruby --version
{% endhighlight %}