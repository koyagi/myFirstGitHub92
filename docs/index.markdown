---
---
# sample markdown

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
