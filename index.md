## Welcome ##

This is the beginning of a website meant to showcase interesting things in the world of data and projects I'm working on related to working with a data source or general python programming. 

***

Some of my favorite websites that use data:
* [The Upshot](http://www.nytimes.com/section/upshot/)
* [Five Thirty Eight](https://fivethirtyeight.com/)

***

Blog coming soon (maybe?)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
