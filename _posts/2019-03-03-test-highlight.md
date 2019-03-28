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

测试一下非常多行的代码块：

{% highlight css linenos %}

eader.post-head {
   margin-bottom: 24px;
   padding: 0;
}
header.post-head .post-title {
   font-weight: normal;
   margin-bottom: 24px;
   display: inline;
}
header.post-head small {
   display: inline;
   font-style: italic;
   margin-left: 20px;
   color: #757575;
}
@media screen and (max-width: 380px){
   header.post-head small {
​      display: block;
​      margin: 1rem 0 1.5rem;
   }
}
.post-content h3, .post-content h4, .post-content h5, .post-content p {
   margin: 10px 0;
}

{% endhighlight %}