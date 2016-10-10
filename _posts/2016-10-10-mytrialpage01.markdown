---
layout: post
title:  "mytrialpage01"
date:   2016-10-10 11:20:00 +0900
categories: jekyll update
---
This is my first trial to make pages with jekyll.

# Title 1

## Title 2

### Title 3

#### Title 4

##### Title 5

###### Title 6

####### Title 7 (may not work)

normal text

This is github fravored markdown code block with c++ highlight

```c++
#include <iostream>

int main(int argc, char** argv) {
    std::cout << "Howdy!" << std::endl;
    return 0;
}
```

This is liquid style code block with c++ highlight

{% highlight c++ %}
#include <iostream>

int main(int argc, char** argv) {
    std::cout << "Howdy!" << std::endl;
    return 0;
}
{% endhighlight %}

This is test for include tag.

{% highlight c++ linenos %}
{% include howdy.cpp %}
{% endhighlight %}

あと、日本語使えますかねぇ？

いや、完璧ちゃう？

次はgithub-pages連携や！
