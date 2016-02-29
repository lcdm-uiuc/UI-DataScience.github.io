---
layout: post
title:  "Hello World!"
date:   2016-02-28 22:01:00 -0600
categories: Initial DataScience
---

Hello, World! This is the first post from the UI-Data Science Blog/News feed. All the members of our group will be able to create markdown files to share their ideas and accomplishments with the outside world. This blog is run with [Jekyll](https://jekyllrb.com/) and the site is hosted by [Github Pages](https://pages.github.com/). The past few weeks have been very humbling as I've tried to get this site and blog off the ground. Finally this hacking endeavor has resulted in this semi-functional tool that I hope our group will use for years to come. Lets take a quick tour of Jekyll's (and markdown's) features.

#### Markdown Styling

I could go through the rigmarole of demonstrating markdown syntax, but [this cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) has already done that for you. Check it out, it's pretty thorough. 

#### Syntax Highlighting

Those familiar with markdown already know of the backticks for code formatting, such as `code` and `directory` and `mv /bin /dev/null` (NEVER execute that in a linux terminal by the way, although it shouldn't let you anyway). But Jekyll has special syntax highlighting dependent on the language (this is Python):

{% highlight python %}
def hello_world(n):
	for i in range(n):
		print('Hello World')
{% endhighlight %}

I'm certainly not a markdown expert, but you get the picture.

#### Creating New Posts

The [Jekyll Docs](http://jekyllrb.com/docs/posts/) do a pretty concise job of explaining how to create posts, and it involves creating a markdown file in a certain directory (`_posts`) following a certain convention. I can picture more than one automated and more user-friendly way of doing that, so that may be an interesting direction to move in the future.

#### Things to Note

Currently only the most recent post will be shown on the front page. The full blog is available through our [blog page](http://ui-datascience.github.io/blog).

-Andrew Mehrmann (github: @dkmehrmann)