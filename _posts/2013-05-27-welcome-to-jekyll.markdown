---
layout: post
title:  "Welcome to Jekyll!"
date:   2013-05-26 16:58:08
categories: jekyll update
---

You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

if you spot following exception:
Liquid Exception: Failed to get header. in `_posts/2013-05-26-welcome-to-jekyll.markdown`
it's caused because Pygments only support Python 2.x and not 3.x. Nasty workaround: sudo ln -sf /usr/bin/python2.7 /usr/bin/python
via https://github.com/tmm1/pygments.rb/issues/45 https://github.com/mojombo/jekyll/issues/1181 https://bbs.archlinux.org/viewtopic.php?id=164528

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com


