## Awesome Python Modules
---
### About this site
Jackkillian.github.io contains fun Python 3.7.2 modules. To install them with pip, run the following  
code on your command line: ```pip install [module name to be installed]``` Or you could download them  
from Github.

## Python Repositories
{% assign items = site.codes | sort: 'title' %}
{% for item in items %}
[{{item.title}}]({{item.url}})
{% endfor %}
