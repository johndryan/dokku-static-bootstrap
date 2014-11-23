# Barebones Bootstrap for Dokku NGINX Static Site

An empty template for a static dokku site.

To be used with [johndryan/buildpack-nginx](https://github.com/johndryan/buildpack-nginx).

## Instructions

To get started, simply:

* clone or download this repo: `git clone git@github.com:johndryan/dokku-static-bootstrap.git`
* `cd dokku-static-bootstrap`
* (if downloaded, don't forget to `git init` and `git commit -am 'Initial commit'`
* add Dokku as a remote: `git remote add dokku dokku@dokku.server:domain.com`
* push to Dokku: `git push dokku master`

You should see a Hello World page by visiting `http://domain.com.dokku.server`.
