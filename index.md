# Welcome to my personal blog

There is nothing for you here yet.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/note-tip-troubleshooting{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
