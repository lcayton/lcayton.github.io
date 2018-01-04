---
layout: default
#title:  "Applied Machine Learning"
date:   2016-03-20 22:30:35 -0700
categories: jekyll update
---
*Please visit the [UW Canvas](http://canvas.uw.edu) page for the full course site*

# Calendar

| Week | Date     | Topic | Projects |
| ---- | --------- | ------- | ------- |
| 1  | 6/23 | [Overview](lectures/overview.html); linear model review | |
| 2  | 6/30 | Featurization: numeric, categorical, and text data; Outputs | Project 1 proposal due |
| 3  | 7/14 | Time series| Project 1 check-in due |
| 4  | 7/7  | Processing raw data; map-reduce and distributed computing; experimental discipline | Project 1 due |
| 5  | 7/21 | Interactions, recommendation systems | Project 2 proposal due |
| 6  | 7/28 | Metrics; models in production | Project 2 check-in due|
| 7  | 8/4  | Modeling big data sets  | Project 2 due |
| 8  | 8/11 | Model understanding | Project 3 proposal due |
| 9  | 8/18 | Understanding data with models; anomaly detection | Project 3 check-in due |
| 10 | 8/25 | Nearest neighbor search; featurizing graphs | Project 3 due|


# Interesting data

* [Election](https://www.kaggle.com/benhamner/2016-us-election). Good working example.
* Climate data. [On kaggle](https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data). See also [Berkeley Earth](http://berkeleyearth.org/data/) for temperature time series at various granularities.
* Health [e.g. chronic disease indicators](http://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi-ff843).
* [Social networks and graphs](https://snap.stanford.edu/data/).
* [Causes of death](https://www.kaggle.com/cdc/mortality) from the CDC/kaggle. Might
be useful for model understanding.
* [Shelter animals](https://www.kaggle.com/c/shelter-animal-outcomes). On-going kaggle competition.
* [Facebook location check-ins](https://www.kaggle.com/c/facebook-v-predicting-check-ins). Good example
for the challenge of targets. Also has a temporality challenge.
* [Project Gutenberg](http://www.gutenberg.org). Text of many books (e.g. Ulysses); great for text
classification.
* Sports: [nfl](http://www.pro-football-reference.com/), [nba](http://www.basketball-reference.com/), [mlb](http://www.baseball-reference.com/).


* Generic data sites:
  * [kaggle](http://kaggle.com)
  * [Census](https://www.census.gov/)
  * [data.gov](http://www.data.gov)
* [Misc text](http://archive.ics.uci.edu/ml/datasets/Bag+of+Words)

{% comment %}

# Trash bin

Lectures
<ul>
{% for page in site.pages %}
  {% if page.categories contains 'lecture' %}
  <li>
    <a href="{{ page.url }}">{{ page.title}}</a>
  </li>	      
  {% endif %}
{% endfor %}
</ul>
Blog posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% endcomment %}
