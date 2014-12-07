---
layout: post
title: "My First Jekyll Post "
comments: true
modified:
categories: posts
excerpt:
tags: []
image:
  feature:
date: 2014-12-07T10:23:07+05:30
---

## My First Mumblings

{% highlight ruby linenos %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}