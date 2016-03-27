---
layout: post

#event information
title:  "NMAP MAC OSX"
cover: "img/hiking-2.jpg"
date:   2016-01-13
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




<h2 class="section-heading">Nmap for Mac Os X - Linux</h2>
<h2 class="section-heading">Nmap Security Scanner for Linux-MAC-UNIX </h2>



<strong> Was ist Nmap ? </strong>


       Nmap ("Network Mapper") ist ein Open-Source-Werkzeug fA1/4r die
       Netzwerkanalyse und SicherheitsA1/4berprA1/4fung. Es wurde entworfen, um
       groAe Netzwerke schnell zu scannen, auch wenn es bei einzelnen Hosts auch
       gut funktioniert. Nmap benutzt rohe IP-Pakete auf neuartige Weise, um
       festzustellen, welche Hosts im Netzwerk verfA1/4gbar sind, welche Dienste
       (Anwendungsname und -version) diese Hosts bieten, welche Betriebssysteme
       (und Versionen davon) darauf laufen, welche Art von
       Paketfiltern/-Firewalls benutzt werden sowie Dutzende anderer
       Eigenschaften. Auch wenn Nmap A1/4blicherweise fA1/4r
       SicherheitsA1/4berprA1/4fungen verwendet wird, wird es von vielen Systemen
       und Netzwerkadministratoren fA1/4r Routineaufgaben benutzt, z.B.
       Netzwerkinventarisierung, Verwaltung von AblaufplAxnen fA1/4r
       Dienstaktualisierungen und die Aberwachung von Betriebszeiten von Hosts
       oder Diensten.



<strong> Install and Set Up </strong>






                              +---------+
        +---------+           | Network |         +--------+
        | server1 |-----------+ swtich  +---------|server2 |
        +---------+           | (sw0)   |         +--------+
                              +----+----+
                                   |
                                   |
                         +---------+----------+
                         | wks01 Linux/OSX    |
                         +--------------------+







<blockquote>
"Learn & Understand how Machine Works!"
</blockquote>
