---
layout: post
title:  博客相关功能测试
tags:  React-Native
categories: [react native]
author: zybug
---


这个是我第一次尝试使用React－Native.

#下面是OC代码显示测试
{% highlight objective-c %} 
- (void)scrollViewDidScroll:(UIScrollView *)scrollView {
    if (scrollView.contentOffset.y <= 0) {
        scrollView.contentOffset = CGPointMake(0, 0);
        return;
    }
}
{% endhighlight %}

![demo image](http://github.zybug.com/images/demo001.png)
