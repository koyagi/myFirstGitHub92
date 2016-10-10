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

[anotherfile](anotherfile.html)

日本語のテスト

c++なんてきらいだー！と何度叫んだことだろう。
そんなことを言いながら、c++に費やしている時間が一番長い気がする。
なんか勿体無い。

しかし、最近ふと気がついた。今のc++は以前よりずっと使いやすくなっている。ただし、自分が知っている古いc++を捨てれば、だ。

