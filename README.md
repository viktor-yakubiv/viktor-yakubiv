[![
    Russia invaded Ukraine,
    killing tens of thousands of civilians
    and displacing millions more.
    It's a genocide.
    Please,
    help us defend freedom, democracy
    and Ukraine's right to exist.
](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-personal-page.svg)](https://vshymanskyy.github.io/StandWithUkraine)

Hello 👋
================================================================

I am an open source developer
with background in software engineering
and passion in user interfaces
and crafting great experiences,
for developers as well as non-tech users.

Currently,
I contribute to open source software
among three categories:
working with abstract syntax trees (ASTs)
enriching the markup data and automatic writing routines,
styling web pages in a plain human language,
sharing my personal workflows and configs for inspiration.
As a member of [Kottans][kottans],
I give lectures focussing on semantics of HTML markup
and the best practices of styling web pages,
mentor students guiding them along web developerʼs path.

Previously,
I was a Head of Web and an author of problems
at [Internet Olympiad in Information Technologies][ioitua],
leading front-end engineer and a product designer
at [CORE][oacore].

[kottans]: https://github.com/Kottans
[ioitua]: https://github.com/ioitua
[oacore]: https://github.com/oacore

Highlighted work
----------------------------------------------------------------

My engineering interests in open source
are shaped among three categories,
described below.

### Transforming ASTs, unified and rehype

Traversing and transformation of abstract syntax trees
for linting and enrichment of simlplified markup
like Markdown to heavy and accessible HTML.

The use-case can be simply found here on GitHub:
in a repository you write a `README.md` in a simple Markdown
markup (GitHub Flavoured Markdown to be precise)
and GitHub converting it to rich HTML in its web interface, 
transforming specific blockquote syntax
to [highlighted notes or warnings][gfm-alerts].

This is achieved by parsing Markdown text into a tree,
transforming it into another AST, e.g. HTML
and transforming it more along the way applying
context-related data and enrichments,
then serialising the tree back to text.
In my work,
I utilize [unified][unifiedjs]ʼs ecosytem,
including [remark][remarkjs] and [rehype][rehypejs]
to do this magic.
Unified.js uses plugins to apply such kind
of AST transformations.
Below,
I list a few ones that I wrote for my needs
and might be useful for you:

<!-- -   hast-util-slots -->
-   [hast-util-merge][] —
    a utility for merging documents or fragments
    in form of [hypertext abstract syntax trees][hast] (HASTs)
-   [rehype-lodash-template][] —
    plugin to replace string values in HTML
    utilizing `lodash.template` function
-   [rehype-postcss][] —
    plugin to process `<style>` elements with PostCSS
-   [rehype-css-modules][] —
    plugin for substituting class names
    with their scoped equivalents (essentially applying CSS modules)
<!-- -   rehype-web-components -->

[gfm-alerts]: https://github.com/orgs/community/discussions/16925
[unifiedjs]: https://github.com/unifiedjs
[remarkjs]: https://github.com/remarkjs
[rehypejs]: https://github.com/rehypejs
[hast]: https://github.com/syntax-tree/hast
[hast-util-merge]: https://github.com/viktor-yakubiv/hast-util-merge
[rehype-lodash-template]: https://github.com/viktor-yakubiv/rehype-lodash-template
[rehype-postcss]: https://github.com/viktor-yakubiv/rehype-postcss
[rehype-css-modules]: https://github.com/viktor-yakubiv/rehype-css-modules

### Styling the Web

Going against common trend in scoped styling
and heavy usage of utility-based CSS,
I develop libraries that focus on:
embracing semantic and accessible markup;
using plain language for definitions;
and applying modern best practices and future technologies.
The goal is to build a solid styling foundation for the Web.
My current work listed below:

-   [css][] —
    a styling library applying modern best practices
    in colours, typography and layout,
    embracing semantic and accessible markup,
    putting it over class-based styling
-   [every-color][] —
    an experimental CSS-library enabling users
    apply colours to text and blocks using plain human language

[css]: https://github.com/viktor-yakubiv/css
[every-color]: https://github.com/viktor-yakubiv/every-color

### Personal workflow enrichments

Sometimes,
I write code to be able to write more code more efficiently.
This is what I did for it so far.

-   [dotfiles][] —
    how I configure my workspace
-   [nvim][] —
    I use Vim (btw);
    here is how I configure it.
-   [brightness.js][] —
    once I needed to synchronise brightness
    of my external display with amount of sunlight along the day
-   [macos.itermcolors][] —
    I like smooth integration of terminal with the colour scheme
    of the operating system but there was no such an option

[dotfiles]: https://github.com/viktor-yakubiv/dotfiles
[nvim]: https://github.com/viktor-yakubiv/nvim
[brightness.js]: https://github.com/viktor-yakubiv/brightness.js
[macos.itermcolors]: https://github.com/viktor-yakubiv/macos.itermcolors
