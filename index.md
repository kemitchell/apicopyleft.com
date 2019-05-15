The latest version is [{{ site.versions.last.number }}]({{ site.versions.last.url }}).

<ul>
  {% for version in site.versions reversed %}
    <li>
      <a href="{{version.url}}">{{version.number}}</a>
    </li>
  {% endfor %}
</ul>

Development continues in [the GitHub repository](https://github.com/kemitchell/api-copyleft-license).
