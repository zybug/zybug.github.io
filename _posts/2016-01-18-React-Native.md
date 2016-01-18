---
layout: post
title:  博客相关功能测试
tags:  测试文章
categories: ［test］ 
author: zybug
---


测试功能是否正常可以使用.

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
