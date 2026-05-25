# Welcome to the DevLog

Here, I share updates from my game development journey.

## Latest Updates:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d.%m.%Y" }}
    </li>
  {% endfor %}
</ul>
