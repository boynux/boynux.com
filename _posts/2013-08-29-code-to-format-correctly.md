---
layout : post
title : How to get code to format correctly
category : Tutorial
tags :
  - tutorial
---

I recently received a quesiton about how to get code to render correctly on a blog post. In order to get the code to render, you'll need to wrap it in and include a blank line before the code block.

For example:

<code>
function code_example() {
  console.log("Showing the rendering of code using gh-pages-blog.");
}
</code>

In order to turn on syntax highlighting, you'll also need to include the language in the first line:

<code>
{% highlight javascript %}
function code_example_with_highlights() {
  console.log("Showing the rendering of code using gh-pages-blog.");
}
{% endhighlight %}
</code>

Dereck
