# brianhenryhf.github.io

This is a Jekyll site deployed using Github Pages (TLS is via Github's use of Let's Encrypt).

Locally, this can be built for developemnt by installing jekyll (via `bundle install`), and then using `bundle exec jekyll b` to build and `bundle exec jekyll b` to serve.

Deployment is via pushing master branch changes, letting implicit GH Pages action run build/deploy steps.
