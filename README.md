# <a href="http://jekyllrb.com" title="Jekyll" target="_blank"><img src="https://raw.githubusercontent.com/ginfuru/vscode-jekyll-snippets/master/images/jekyll-logo.png" atl="Jekyll Logo" width="250"></a> snippets package for Visual Studio Code.

[![GitHub release](https://img.shields.io/github/release/ginfuru/vscode-jekyll-snippets.svg)](https://github.com/ginfuru/vscode-jekyll-snippets/releases)

Jekyll snippets for Visual Studio Code. This is a combination of both the the [sublime-jekyll package](https://github.com/23maverick23/sublime-jekyll)
by [@23maverick23.](https://github.com/23maverick23) and the [atom-jekyll package](https://atom.io/packages/jekyll-snippets) by [@jasonhodges](https://github.com/jasonhodges).

## HTML, Jekyll Lang and Markdown Support

* **Support for markdown has also been added**, which was referenced in issue [#7](https://github.com/ginfuru/vscode-jekyll-snippets/issues/7) by [@Haroenv](https://github.com/Haroenv). I haven't found a markdown grammer file that highlights liquid syntax.

     If you want to have snippets suggestions as you type, you'll need to add the below to your global settings or workspace settings:
     ```
     {
      "[markdown]": {
          "editor.quickSuggestions": true
       }
     }
     ```
     Alternatively, you can also use the keyboard trigger `ctrl+ space`

* **Support for html has been added**, due to some odd behavior from other extenions I use which doesn't provide support for `liquid` file extension.


## Roadmap & Contributing

I do have plans to continue adding more snippets, based on the [Jekyll Tips Cheat Sheet](http://jekyll.tips/jekyll-cheat-sheet/), but **PLEASE** feel free to contribute and/or file issues with requests. If you do want to contribute please make sure to create a feature branch and when creating a pull request to rebase or squash prior to.

> ##### Thanks again to [@23maverick23.](https://github.com/23maverick23) and [@jasonhodges](https://github.com/jasonhodges)
