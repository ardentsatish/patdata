---
layout: post
title: Adding Content
author: Srihari
---
Hello there,

Well, this post intends to get you started on using the blog. Currently, it's hosted as a Github Page in my repository. For you to start contributing to the blog, tell me your Github ID, and I can add you as a 'Collaborator' to this repo, after which you can easily start adding posts.

To add a post you need to go to [this](https://github.com/rsrihari/patdata/tree/gh-pages/_posts) directory in the repo, and use the '+' to add a new post. At the top of the new file you are writing, add a header similar to this:

{% highlight python %}
---
layout: post
title: Adding Content
author: Srihari
---
{% endhighlight %}

'layout' should always be 'post' while you should take care of the other two. Add the rest of the content in Markdown. There is a good [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for quickly working with Markdown by Adam Pritchard. But since this blog is hosted using Jekyll, you would need to take care at some places where the markdown syntax would not work. For example, the original markdown way of adding code to the document, differs from the manner in which you add code in a markdown file for a post in Jekyll page. See this [post](https://raw.githubusercontent.com/rsrihari/patdata/gh-pages/_posts/2015-05-01-guidelines.md) as an example. After you are done writing the post, save the file with name in this format : `yyyy-mm-dd-name-of-post.md` . Commit the changes
