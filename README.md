##  [Technologie Internetowe](ug.geojson), 14/15

Linki do projektów na zaliczenie z przedmiotu „Techniki Internetowe”:

    1. [Nazwisko, Imię](link do swojej strony w domenie github.io)
      - [README.md](link), [README.asc](link)
      - [Tytuł pokazu slajdów](link)
      - [Moje notatki z...](link)

1. Erdanowski, Tomasz 12.04
1. Gisko, Alicja
1. Jacewicz, Małgorzata
1. Łuksza, Natalia
1. Nowak, Łukasz
1. Nowicka, Beata
1. Ostapczuk, Andrzej
1. [Selke, Marcin](http://mselke.github.io/)
1. Skuza, Łukasz
1. Sudomir-Gordon, Milena
1. Mokrzycki, Rafał
2. [Snarski, Lech](http://lsnarski.github.io/)
3. [Erdanowski, Tomasz](http://terdanowski.github.io/)


### Linki

1. Sigma:
  - [Konfiguracja](https://inf.ug.edu.pl/konfiguracja); u dołu strony
  jest informacja dla studentów – loginy, adresy majlowe, stron domowych
  - [Bash](http://wbzyl.inf.ug.edu.pl/sp/unix-commands)
1. Git:
  - [ProGit Book, v2](http://git-scm.com/book/en/v2)
  - [Using pull requests (on GitHub)](https://help.github.com/articles/using-pull-requests/)
  - [Konfiguracja](http://wbzyl.inf.ug.edu.pl/sp/git)
1. Markdown na GitHub:
  - [Syntax](http://daringfireball.net/projects/markdown/syntax)
  - [GitHub Flavored Markdown](http://guides.github.com/overviews/mastering-markdown/)
  - [Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github)
1. AsciiDoc:
  - [Asciidoctor](http://asciidoctor.org)
  - [AsciiDoc User’s Guide](http://asciidoctor.org/docs/asciidoc-writers-guide/)
  - [HubPress](https://github.com/HubPress/hubpress.io)
1. Slajdy:
  - [Reveal.js](http://lab.hakim.se/reveal-js/) oraz [Slides](http://slid.es/)
1. [Meteor Framework](https://www.meteor.com/)
  - David Turnbull.
    [Your First Meteor Application](http://meteortips.com/book/) –
    a complete beginner’s guide to the Meteor JavaScript Framework
  - [Discover Meteor](http://book.discovermeteor.com/) – książka
    ([polskie tłumaczenie](http://pl.discovermeteor.com/))


### Użyteczne narzędzia

- [Atom](https://atom.io) – a hackable text editor for the 21st Century:
  - [Atom Flight Manual](https://atom.io/docs/latest/) – the latest version
  - packages: [language-asciidoc](https://atom.io/packages/language-asciidoc),
    [asciidoc-preview](https://atom.io/packages/asciidoc-preview)
  - themes: seti-syntax, seti-ui, monokai, monokai-inverted
  - [keyboard shortcuts](https://github.com/nwinkler/atom-keyboard-shortcuts)
- Jekyll: [jekyll-asciidoc](https://github.com/asciidoctor/jekyll-asciidoc),
  [jekyll-asciidoc-quickstart](https://github.com/asciidoctor/jekyll-asciidoc-quickstart)
- [Secure Shell](http://en.wikipedia.org/wiki/Secure_Shell)
  (klucz publiczny, klucz prywatny; generowanie kluczy)
- [GitHub Desktop](http://windows.github.com/)


### Zrób to sam

- [JS Bin](http://jsbin.com/) – collaborative JavaScript Debugging
- [CodePen](http://codepen.io/) – front end developer playground & code editor in the browser
- [Adobe Kuler](https://kuler.adobe.com/create/color-wheel/) – color wheel and schemes
- [Reply.it](http://repl.it/languages/JavaScript)
- Atom: zmieniamy wielkość fontu w widoku „tree”, wklejając w pliku
  *~/.atom/styles.less* ten kod:

```less
@tree-view-font-size: 14px;
@tree-view-line-height: 28px;

.tree-view {
  font-size: @tree-view-font-size;

  .list-group li:not(.list-nested-item),
  .list-tree li:not(.list-nested-item),
  .list-group li.list-nested-item > .list-item,
  .list-tree li.list-nested-item > .list-item {
    line-height: @tree-view-line-height;
  }
  .list-group .selected::before,
  .list-tree .selected::before {
    height: @tree-view-line-height;
  }
}
```
Przedefinowujemy w pliku *keymap.json* (Settings>Keybindings)
skrót do Command Palette:

```yaml
'.platform-linux':
  'cmd-shift-p': 'command-palette:toggle'
```

Do pliku *~/.atom/snippets.cson* dopisujemy dwa snippety:

```yaml
'.source.asciidoc':
  'Relative link':
    'prefix': 'link'
    'body': 'link:$1[$2]'
  'Code block with title and syntax highlighting':
    'prefix': 'ch'
    'body': '[source,$1]\n----\n$0\n----'
```

## Rozkład zajęć

1\. Git:

- Zakładamy konto na serwerze GitHub
- Tworzymy pierwsze repozytorium na GitHub
- [GitHub Guides](https://guides.github.com/)
- [Got 15 minutes and want to learn Git?](http://try.github.io/levels/1/challenges/1)

2\. HTML & CSS

- [HTML 5 Outliner](https://gsnedders.html5.org/outliner/);
  [Chrome extension](https://chrome.google.com/webstore/detail/html5-outliner/afoibpobokebhgfnknfndkgemglggomo)
- [Thinkful HTML](https://github.com/mjhea0/thinkful-html) –
  wprowadzenie do HTML i CSS
  - [Web Design/HTML Challenges](http://en.wikiversity.org/wiki/Web_Design/HTML_Challenges)
- [Learn CSS Layout](http://learnlayout.com/)

3\. HTML5

- [HTML5 element list](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5/HTML5_element_list) –
  [MDN](https://developer.mozilla.org/pl/) (Mozilla Developer Network)
- [HTML5 Element Index](http://html5doctor.com/element-index/)
- [HTML4 Element Index](http://www.w3.org/TR/html4/index/elements.html)
- [To close or not to close](http://www.colorglare.com/2014/02/03/to-close-or-not-to-close.html)
- Tommi Kaikkonen:
  * [Interactive Guide to Blog Typography](http://www.kaikkonendesign.fi/typography/)
  * [Why Websites Are White](http://www.kaikkonendesign.fi/why-websites-are-white/)
- [Materialize](http://materializecss.com) –
  a modern responsive front-end framework based on
  [material design](http://www.google.com/design/spec/material-design/introduction.html);
  zob. też [Make Material Design Websites with the Materialize CSS Framework](https://scotch.io/tutorials/make-material-design-websites-with-the-materialize-css-framework)

4\. CSS3

- [Bootstrap](http://getbootstrap.com)
  - [Less](http://lesscss.org) (LessCSS czy Less.js)
- [Foundation](http://foundation.zurb.com)
- [Cascading Style Sheets](http://www.w3.org/Style/CSS/)
- [Getting started with CSS](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Getting_started)
- [CSS Diner](http://flukeout.github.io/) – where we feast on CSS Selectors!

5\. [Web Components](http://webcomponents.org)

- [Polymer project](https://www.polymer-project.org/0.5/) (v0.5.5)
- [Polymer repository](https://github.com/Polymer/polymer)
- [Custom Elements](http://customelements.io/) –
  a Web Components Gallery for modern web applications
- [Web Components](https://chrome.google.com/webstore/detail/web-components/filcobblndaenakhejinpjdblekilpgn) – Chrome Extension

6\. JavaScript

- Marijn Haverbeke. [Eloquent JavaScript](http://eloquentjavascript.net/) –
  A Modern Introduction to Programming


### JavaScript Extras

Firefox extensions:
- [Firebug](https://addons.mozilla.org/en-US/firefox/addon/firebug/)
- [Firebug Command Line API](https://getfirebug.com/wiki/index.php/Command_Line_API)

[Node.js](http://nodejs.org/):
```console
alias node="env NODE_NO_READLINE=1 rlwrap node"
```

- Kyle Simpson. [You Don’t Know JS](https://github.com/getify/You-Dont-Know-JS)
- [MDN & JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  - [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array)
- John Resig.
  [Secrets of the JavaScript Ninja](http://ejohn.org/apps/learn/) – funkcje w JavaScript
