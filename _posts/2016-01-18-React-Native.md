---
layout: post
title: React-Native 学习
tags:  React-Native
categories: [React-Native]
author: zybug
---


这个是我第一次尝试使用React－Native.

####下面是OC代码显示测试
{% highlight objective-c %} 
- (void)scrollViewDidScroll:(UIScrollView *)scrollView {
    if (scrollView.contentOffset.y <= 0) {
        scrollView.contentOffset = CGPointMake(0, 0);
        return;
    }
}
{% endhighlight %}
