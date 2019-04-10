---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: page
---
## Awesome Python Modules
---
### About this site
Jackkillian.github.io contains fun Python 3+ modules.

## Python Repositories
{% assign items = site.codes | sort: 'title' %}
{% for item in items %}
[{{item.title}}]({{item.url}})
{% endfor %}
