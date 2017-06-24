# <a href="http://jekyllrb.com" title="Jekyll" target="_blank"><img src="http://jekyllrb.com/img/logo-2x.png" atl="Jekyll Logo" width="250"></a> snippets package for Visual Studio Code.

[![GitHub release](https://img.shields.io/github/release/ginfuru/vscode-jekyll-snippets.svg)](https://github.com/ginfuru/vscode-jekyll-snippets/releases)

Jekyll snippets for Visual Studio Code. This is a combination of both the the [sublime-jekyll package](https://github.com/23maverick23/sublime-jekyll)
by [@23maverick23.](https://github.com/23maverick23) and the [atom-jekyll package](https://atom.io/packages/jekyll-snippets) by [@jasonhodges](https://github.com/jasonhodges).

## HTML, Liquid, and Markdown Support

If you are downloading the extension for the first time you'll be prompted that the [Liquid Languages Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid) will also be installed. This happens because of the `extensionDependencies` which elminates the need to manaully fetch another extension, which was referenced in issue [#3](https://github.com/ginfuru/vscode-jekyll-snippets/issues/3) by @graffen.

#### Why you might want liquid extension?

1. ✔ Provides syntax highlighing for your liquid tags.
2. ✔ Provides liquid extension and support.
3. ✔ Provide syntax highlighting for liquid tags - ie: `{{ site.baseurl }}` & `{% for something in this_file %} {% endfor %}`
     * By changing your `HTML` syntax to `HTML(Liquid)`


* **Support for markdown has also been added**, which was referenced in issue [#7](https://github.com/ginfuru/vscode-jekyll-snippets/issues/7) by [@Haroenv](https://github.com/Haroenv). I haven't found a markdown grammer file that highlights liquid syntax.

* **Support for html has been added**, due to some odd behavior from other extenions I use which doesn't provide support for `liquid` file extension.

## Optional Extensions to install
 As noted by [@Serhioromano](https://github.com/Serhioromano) in issue #8, formatting for front-matter and liquid tags are not supported by the default formatter for VSCode _(JS-Beautify)_ this is resolved by installing [vscode-prettydiff](https://marketplace.visualstudio.com/items?itemName=HexcodeTechnologies.vscode-prettydiff).


## Roadmap & Contributing

I do have plans to continue adding more snippets, based on the [Jekyll Tips Cheat Sheet](http://jekyll.tips/jekyll-cheat-sheet/), but **PLEASE** feel free to contribute and/or file issues with requests. If you do want to contribute please make sure to create a feature branch and when creating a pull request to rebase or squash prior to.

> ##### Thanks again to [@23maverick23.](https://github.com/23maverick23) and [@jasonhodges](https://github.com/jasonhodges)
