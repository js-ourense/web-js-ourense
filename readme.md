Web del grupo de usuarios de JavaScript de Ourense, la puedes ver en [ourense.javascript.gal](http://ourense.javascript.gal).

Esta creada con Hexo y el tema esta basado en el [tema Apollo](https://github.com/pinggod/hexo-theme-apollo).

En la rama master está el código que genera la web (markdown, Sass, etc...) y en la rama gh-pages tenemos el html y css ya generado.

## Instalación

Instala [Hexo](https://hexo.io/docs/index.html)

`$ npm install -g hexo-cli`

Instala todas las dependencias

`$ npm install`

Ya está, para probar en local simplemente:

`$ hexo server`

## Uso

Si quieres escribir un post puedes hacerlo con:

`$ hexo new post mi-post`

Para publica usamos [hexo-deployer-git](https://github.com/hexojs/hexo-deployer-git) así que

`$ hexo generate -d`

debería generar de nuevo la web y publicarla a la rama gh-pages. No te olvides de pushear el post también a la master.
