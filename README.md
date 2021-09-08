# Guía de uso

Para desarrollar y hacer preview es necesario instalar Ruby. Conviene configurar Ruby para que instale gems en el HOME:

    export BUNDLE_PATH=~/.gem

Luego crear un archivo ~/.gemrc y agregar:

    gem: --no-document
    gem: --user-install


Agregar al PATH el directorio local de gems (ajustar de acuerdo a la versión de Ruby): 

    export PATH=$PATH:~/.gem/ruby/3.0.0/bin

Finalmente se puede instalar bundler (similar a npm de NodeJS) y jekyll (generador de páginas Web):

    gem install bundler
    gem install jekyll

Para previsualizar el sitio web:

    BUNDLE_GEMFILE=Gemfile-dev bundle exec jekyll serve --livereload

Para regenerar el índice del buscador:

    BUNDLE_GEMFILE=Gemfile-dev ALGOLIA_API_KEY='CLAVE SUPER SECRETA...' jekyll algolia

Esto puede fallar si hay páginas con mucho texto (plan gratis de agolia) en cuyo caso se puede eliminar temporariamente contenido (ej: en rrhh.md se puede quitar todo el detalle después de los nombres) 

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
