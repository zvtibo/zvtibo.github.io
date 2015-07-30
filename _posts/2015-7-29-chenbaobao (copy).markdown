---
layout: post
title:  "中英文 "
date:   2015-07-28 23:41:08
categories: rails
---
这样，理论上，浏览器会优先用英文字体显示文字，英文字体里没包含的字符，则从后面的中文字体里面找，这样就达到了中英文显示不同字体的效果（具体到各个操作系统和浏览器，还有不少差别，可参见 jjgod 的《浏览器如何渲染文本》）。比如上面的例子就是英文用 Arial，汉字用宋体。

这样的问题是：1，各个系统和浏览器的行为不同，有的用后面规定的中文字体，有的会用浏览器或系统默认字体。2，有的字符，可能英文字体和中文字体里都有，于是想用中文字形却显示成了英文字形。
<!-- more -->
Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight python%}
def print_hi(name)
	print "Hi" + name
print_hi("heihei")
{% endhighlight %}

I'm baby!

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help