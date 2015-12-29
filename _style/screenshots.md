---
title: Screenshots
---

Take screenshots free of any browser window or OS involved. CloudCannon works the same on all devices as a native app or in a browser. Wrap all screenshots in a basic window seen below.

![An example CloudCannon screenshot](/img/style/screenshot.png){: .screenshot}{: .classa }

This is done to ensure:

* There is no problem displaying them on white
* It allows the image to standout with a clear differentiation from the text


Achieve this without any extra markup by using borders and a background image.

{% highlight css %}
.screenshot {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
    background-color: #ddd;
    box-shadow: 0 1px 0 #ccc, 0 1px 1px #eee;
    border-radius: 2px;
    padding: 20px 0 0 0;
    background: #DDD url(/img/icons/browser-buttons.svg) 4px 4px no-repeat;
}
{% endhighlight %}