## Welcome ##

This is the beginning of a website meant to showcase interesting things in the world of data as well as projects I'm working on involving data analysis or general python programming. 


<hr>
Some of my favorite websites that use data:
* [The Upshot](http://www.nytimes.com/section/upshot/)
* [Five Thirty Eight](https://fivethirtyeight.com/)
* [USA Facts](https://usafacts.org/)
* [OECD Data](https://data.oecd.org/)
* [ProPublica Data](https://www.propublica.org/datastore/)
<hr>

|table try|one more|
|huh|does this work|

Blog coming soon (maybe?)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
