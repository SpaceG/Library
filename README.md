# Library Amokläufer V.0.1
Library - Rails on Ruby - Jekyll Theme
Preview: http://www.blog.lucasgatsas.ch

Clone to Desktop
<code>git clone https://github.com/SpaceG/library.git  </code>
Delete the cname file.


<code>cd Desktop </code><br>
<code>cd library </code><br>
<code>$ jekyll serve </code>

watch your localhost <code> 127.0.0.1:8080 </code>


to but the code in a static html file :
<code>
{% highlight ruby linenos %}
// array literlas
  var = empty = [];
  var = numbers = [
  'zero', 'one', 'two', 'three', 'four',
  'five', 'six', 'seven', 'eight', 'nine'
  ];
  empty[1] // undefined
  numbers[1] // 'one'
  empty.lenght // 0
  numbers.lenght //10
{% endhighlight %}

{% highlight ruby linenos %}
  // The Object Literal
  var numbers_object = {
    '0': 'zero', '1': 'one', '2': 'two',
    '0': 'three', '4': 'four', '5': 'five',
    '6': 'six', '7': 'seven', '8': 'eight',
    '9': 'nine'
  };
{% endhighlight %}
</code>





The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
