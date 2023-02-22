CzarDAO.org
===========

Website powered by Hugo and hosted at [CzarDAO.org](https://czardao.org).

Building the Site
---------------

This site is built with Hugo, a static-site generator. To get this repository
and the website theme:

```
git clone git@github.com:czar-dao/czardao.org.git
git submodule update --init
```

Then do either `hugo serve` to host the content at localhost:1313 or simply
`hugo` to build to the `public/` directory.

Hosting
-------

Run `hugo` then host the `public/` directory with a webserver like nginx.

License
-------

MIT License (see `/LICENSE`)
