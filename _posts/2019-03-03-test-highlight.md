---
layout: post
title: 代码高亮测试文档
---

先来测试一段代码：

{% highlight python linenos %}

from flask import Flask
app = Flask("__name__")

@app.route("/")
def index():
​	return "Hello, World!"

{% endhighlight %}

再来一个单行的代码

{% highlight python %}

print("Hello, World!")

{% endhighlight %}