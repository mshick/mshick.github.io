---
title: Welcome!
date: '2016-08-11 00:00:00'
layout: page
body_class: body--homepage
---

### I am

* Technical Director at [Ronik Design](http://www.ronikdesign.com)
* Great with React, Node.js, AWS, generators, content-management systems,     relational and object databases
* Writing in Javascript, Ruby, PHP
* Pleased to meet you 👋

### Contact me

* Email: [m@shick.us](mailto:m@shick.us)
* Phone: [+1 347-987-0104](tel:+13479870104)
* GitHub: [mshick]({{ site.github.owner_url }})

{% if site.posts | length %}
### Latest posts

{% for post in site.posts limit:3 %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}
{% endif %}
