--- layout: page title: Staff description: Meet our team. permalink: /staff/ menu: true ---

# Staff

<div class="staff">{% for author in site.authors %}

<div class="item">

## [{{ author.display_name }}]({{ site.baseurl }}{{ author.url }})

{% if author.position %}

### {{ author.position }}

{% endif %}</div>

{% endfor %}</div>
