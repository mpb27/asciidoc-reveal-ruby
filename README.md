[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/mpb27/asciidoc-reveal-ruby)

# asciidoc-reveal-ruby
Playing with Reveal for AsciiDoc using Ruby.

Instructions

1. `gem install bundler`
1.  
```bash
mkdir my-awesome-presentation 
cd my-awesome-presentation
```

gem install asciidoctor-diagram


bundle config --local github.https true
bundle --path=.bundle/gems --binstubs=.bundle/.bin


`git clone -b 3.9.2 --depth 1 https://github.com/hakimel/reveal.js.git`

`gem install asciidoctor-revealjs`

1. `gem install asciidoctor-kroki`
2. ` gem install asciidoctor-diagram`


`bundle exec asciidoctor-revealjs SLIDES.adoc`
`bundle exec asciidoctor-revealjs -r asciidoctor-kroki SLIDES.adoc`

