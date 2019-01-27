# <a href="http://jekyllrb.com" title="Jekyll" target="_blank"><img src="https://raw.githubusercontent.com/ginfuru/vscode-jekyll-snippets/master/images/jekyll-logo.png" atl="Jekyll Logo" width="250"></a> package for Visual Studio Code.

[![GitHub release](https://img.shields.io/github/release/ginfuru/vscode-jekyll-snippets.svg)](https://github.com/ginfuru/vscode-jekyll-snippets/releases)

A Visual Studio Code package for Jekyll static sites and blogs.

## Features
1. Create a new jekyll site
2. Create posts
3. Build site
4. Start and Stop the server
5. Jekyll Snippets - _(supports HTML/Markdown/Jkeyll Syntax)_


If you are downloading the extension for the first time you'll be prompted that the [Jekyll Syntax Support](https://marketplace.visualstudio.com/items?itemName=ginfuru.ginfuru-vscode-jekyll-syntax) extension will also be installed. This happens because of the `extensionDependencies` which elminates the need to manaully fetch another extension, which was referenced in issue [#3](https://github.com/ginfuru/vscode-jekyll-snippets/issues/3) by @graffen.

#### Why you might want Jekyll Syntax extension?

1. ✔ Provides syntax highlighing **Front Matter**.
2. ✔ Provides jekyll extension and support on HTML files.
3. ✔ Provide syntax highlighting for _jekyll supported_ liquid tags - ie: `{{ site.baseurl }}` & `{%- for something in this_file -%} {%- endfor -%}`
     * By changing your `HTML` syntax to `Jekyll (HTML)`


* **Support for markdown has also been added**, which was referenced in issue [#7](https://github.com/ginfuru/vscode-jekyll-snippets/issues/7) by [@Haroenv](https://github.com/Haroenv). I haven't found a markdown grammer file that highlights liquid syntax.

* **Support for html has been added**, due to some odd behavior from other extenions I use which doesn't provide support for `liquid` file extension.


## Roadmap & Contributing

I do have plans to continue adding more snippets and other feaatures, based on the CloudCannon [Jekyll Cheat Sheet](https://learn.cloudcannon.com/jekyll-cheat-sheet/), but **PLEASE** feel free to contribute and/or file issues with requests.

> #### Thanks again to [@23maverick23.](https://github.com/23maverick23) and [@jasonhodges](https://github.com/jasonhodges)
>This is a combination of both the the [sublime-jekyll package](https://github.com/23maverick23/sublime-jekyll)
by [@23maverick23.](https://github.com/23maverick23) and the [atom-jekyll package](https://atom.io/packages/jekyll-snippets) by [@jasonhodges](https://github.com/jasonhodges).
