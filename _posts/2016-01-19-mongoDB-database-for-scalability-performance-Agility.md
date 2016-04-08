---
layout: post

#event information
title:  "Mongo DB"
cover: "img/lg.jpg"
date:   2015-07-07
start_time: "10:00"
end_time: "17:00"

#event organiser details
organiser: "Lucas Gatsas"


---




{% highlight ruby linenos %}
// integer
      var test = 1;
      // float
      var floatWert = 1023.23345489;
      // NuN
      var geteiltDurchZwei = 42 / 2;
      if (isNaN(geteiltDurchZwei)) {
          document.write("ungültige Number <br>");
      } else {
        document.write("geteiltdurchZwei; "  + geteiltDurchZwei + "<br>")
      }
{% endhighlight %}

{% highlight ruby linenos %}
// string
      var eineZeichenkette = "meineZeichenkette";
      var eineZeichenketteEins = "ist Toll";
      document.write(eineZeichenkette + " " + eineZeichenketteEins + "<br>");
{% endhighlight %}

{% highlight ruby linenos %}
// Boolean  (Ja = 1 / Nein = 0 )
    var boolscherWert = true;
    if (boolscherWert == 1) {
      document.write("boolscherWert ist 1 <br>");
    }
{% endhighlight %}

{% highlight ruby linenos %}
// array / Liste
      var meinArray = [1, 2, 3, "test", 12.34];
      document.write("element: " + meinArray [0] + "<br>");
{% endhighlight %}

{% highlight ruby linenos %}
// associative array
  var person = { name: "Lucas", alter: 30  };
  document.write (person ["name"] + "<br>" + ["alter"]);
{% endhighlight %}



<blockquote>
"Learn & Understand how Machine Works!"

</blockquote>
