Ce dépot est le site internet des Rencontres Utilisateurs Francophone de QGIS. Il est basé sur le thème Cayman, https://github.com/lorepirri/cayman-blog et est hébergé par Github pages.

Pour construire le site localement :

- Sous ubuntu/debian,
`sudo apt-get install jekyll`
 puis
`bundle3.0 exec jekyll serve
`
- Autres méthodes : https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

- avec docker : 
depuis le répertoire courant de ce projet :

`docker run --rm --volume="$PWD:/srv/jekyll" --volume="$PWD/vendor/bundle:/usr/local/bundle" --env JEKYLL_ENV=development -p 4000:4000 jekyll/jekyll:3.8 jekyll serve`
