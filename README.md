# ic-travis-pelican-github-pages
Integración continua: Travis, pelican, Github Pages

1. Instalo en un virtualenv pelican
2. Creo un repositorio en github
3. Genero página con pelican en el repositorio, pongo el server https://www.fullstackpython.com/blog/generating-static-websites-pelican-jinja2-markdown.html
4. http://blog.mathieu-leplatre.info/publish-your-pelican-blog-on-github-pages-via-travis-ci.html
5. Creo la rama gh-pages en el repositorio:

	git checkout -b gh-pages
	git rm -rf *
	git commit -am "Borro gh-pages"
	git push origin gh-pages