---
layout: default
title: Nathan Crowder
---

## Welcome ##

This is the beginning of a website meant to showcase interesting things in the world of data as well as projects I'm working on involving data analysis or general python programming. 


<hr>
Some of my favorite websites that use data:

|[The Upshot](http://www.nytimes.com/section/upshot/) | [Five Thirty Eight](https://fivethirtyeight.com/)
|[USA Facts](https://usafacts.org/) | [OECD Data](https://data.oecd.org/)
|[ProPublica Data](https://www.propublica.org/datastore/) | [KD Nuggets](http://www.kdnuggests.com)
|[Rand](http://www.rand.org) | [Pew Research Center](https://www.pewresearch.org/)
|[Simply Stats](https://simplystatistics.org/about/)

Interesting problems:
* [The German Tank Problem](https://www.eadan.net/blog/german-tank-problem/)
* [Prisoner's Dilemma](http://www.jstor.org/stable/173932?origin=JSTOR-pdf)

Sites for learning:
* [Google Sheets](https://www.benlcollins.com/)
* [Kaggle mini courses](https://www.kaggle.com/learn/overview)
* [AutoHotKey](https://www.autohotkey.com/docs/Tutorial.htm)
* [Code Geekdom](https://www.geeksforgeeks.org/working-csv-files-python/)

Wanna learn, host, and run your code online without installing? [Python Anywhere](https://www.pythonanywhere.com/user/ncrowder/)
<hr>

Blog coming soon (maybe?)
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>