[comment]: <> (---)

[comment]: <> (layout: page)

[comment]: <> (permalink: /repositories/)

[comment]: <> (title: Repositories)

[comment]: <> (nav: true)

[comment]: <> (nav_order: 3)

[comment]: <> (---)

[comment]: <> (## GitHub users)

[comment]: <> ({% if site.data.repositories.github_users %})

[comment]: <> (<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">)

[comment]: <> (  {% for user in site.data.repositories.github_users %})

[comment]: <> (    {% include repository/repo_user.html username=user %})

[comment]: <> (  {% endfor %})

[comment]: <> (</div>)

[comment]: <> ({% endif %})

[comment]: <> (---)

[comment]: <> (## GitHub Repositories)

[comment]: <> ({% if site.data.repositories.github_repos %})

[comment]: <> (<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">)

[comment]: <> (  {% for repo in site.data.repositories.github_repos %})

[comment]: <> (    {% include repository/repo.html repository=repo %})

[comment]: <> (  {% endfor %})

[comment]: <> (</div>)

[comment]: <> ({% endif %})
