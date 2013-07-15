# Semantic Jekyll theme

This is my Jekyll theme that I use with [Jekyll Bootstrap](jekyllbootstrap.com). The themes that come with JB all use divs for structure and don't include any [WAI ARIA roles](http://www.w3.org/TR/wai-aria/roles). This theme uses more modern [HTML5 sectioning elements](http://www.w3.org/TR/2010/WD-html5-20101019/sections.html) for structure and gives them their appropriate roles.

CSS comes from the Tom theme, which is included in Jekyll Bootstrap.

I'm not entirely used to these new sections and roles, so if you see
something I could do better, please send a pull request.

## Usage

In your Jekyll Bootstrap directory, run this command:

    rake theme:install git="https://github.com/IanWhitney/semantic_jekyll.git"

That will install the theme and ask you if you want to switch. If you
want to customize anything, change the files in
_includes/themes/semantic_jekyll or assets/themes/semantic_jekyll.
