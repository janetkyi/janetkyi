---
layout: post
title: Boring science- for everyone who hates science 
subtitle: it's a good read i promise you 
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

This is a demo post to show you how to write blog posts with markdown.  I strongly encourage you to [take 5 minutes to learn how to write in markdown](https://markdowntutorial.com/) - it'll teach you how to transform regular text into bold/italics/headings/tables/etc.

**Here is some bold text**

## Here is a secondary heading

Here's a useless table (disclosure none of this is factual info):

| How many people care | Science Majors | Non-science |
| :------ |:--- | :--- |
| Boomers | 40% | 0% |
| Gen X | 50% | 10% |
| Millenials | 79.5%  | 20.5% |
| Gen Z | 99.9% | .1% |


What life was like before COVID-19

![Crepe](https://viewofthearts.files.wordpress.com/2019/06/img_2379.jpg){: .mx-auto.d-block :}

Life with COVID-19!

![Crepe](https://images.theconversation.com/files/332607/original/file-20200505-83757-s7cflj.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
