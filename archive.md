# Archive

<nav>
  <ul>
  {% for post in site.posts limit:10 %}
      <a href="{{ post.url }}">
        {% if post.link %}
          {{ post.link }}
        {% else %}
          {{ post.title }}
        {% endif %}
      </a>
    </li>
  {% endfor %}
  </ul>
</nav>