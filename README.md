## Symbols for [@trytoprogram](https://twitter.com/trytoprogram)

I'm trying to make a list of some low-level ideas and issues in programming that
I can compose together to reveal larger questions.

<ul>
{% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
{% endfor %}
</ul>
