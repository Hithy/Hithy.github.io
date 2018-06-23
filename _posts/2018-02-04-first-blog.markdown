---
layout: post
title:  "First blog"
date:   2018-02-04 12:23:55 +0800
categories: tech
---

## 折腾
### 记录

{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}