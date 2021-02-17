---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <a href="{{author.googlescholar}}">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-publication.html %}
{% endfor %}

<script type="text/javascript">
	document.querySelector("link[rel='shortcut icon']").href = "{{ base_path }}/images/publicationicon.png";
	document.querySelector("link[rel*='icon']").href = "{{ base_path }}/images/publicationicon.png";
</script>