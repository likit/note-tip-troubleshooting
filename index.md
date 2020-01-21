## Welcome to my personal blog for tips, notes for troubleshooting and stuff

{% for post in site.posts %}   
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong></p>            
{% endfor %}
