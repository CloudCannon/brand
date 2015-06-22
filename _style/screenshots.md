---
title: Screenshots
---

Screenshots should always be taken free of any browser window or OS involved. CloudCannon works the same on all devices as a natively wrapped app or in a browser. All screenshots should be wrapped inside of a basic window seen below.

<img class="screenshot" src="/img/style/screenshot.png" alt="An example CloudCannon screenshot">

This is done to ensure:

* There is no problem displaying them on white
* It allows the image to standout with a clear differentiation from the text

This can be achieved with out any additional markup by using borders and a background image.

{% highlight css %}
.screenshot {
    max-width: 100%;
    height: auto;
    display: block;
    margin: 0 auto;
    background-color: #DDD;
    box-shadow: 0 1px 0 #ccc, 0 1px 1px #eee;
    border-radius: 2px;
    padding: 20px 0 0 0;
    background: #DDD url(/img/icons/browser-buttons.svg) 4px 4px no-repeat;
}
{% endhighlight %}
