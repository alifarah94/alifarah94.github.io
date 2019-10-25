---
layout: post
title: Test markdown
subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---



**Here is some bold text**

## Who wins in Sumo

Sumo wrestling is said to have been made 2000 years ago, rich in culture and deeply ingrained in the Japanese society it is now the national sport. 

What intrigues me about sumo wresting is that there are no weight classes, everyone is able to fight everyone and what dictates who fights who is based on win/loss record in the tournament.
(https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwjVp-7g9rflAhXuzoUKHTUIAHAQjRx6BAgBEAQ&url=https%3A%2F%2Fbjj-world.com%2Ftakanoyama-shuntaro-aka-pavel-bojar-smallest-sumo-champion%2F&psig=AOvVaw1T_o4IBpepVJlv_HhAJxz1&ust=1572110661273411)


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .center-block :}

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
