# Change Log

All notable changes to the "jekyll-snippets" extension will be documented in this file.

## V 0.9.3 03-19-2020

- Update readme to showcase how to get the `quickSelections` to work for markdown files

## V 0.9.2 02-20-2020

- removes Jekyll Syntax as a dependency -- I do suggest using [Liquid Language Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid) over-top of Jekyll Syntax 😬

## V 0.9.1 02-18-2019

- fixes typos introduced in `V0.9.0` - thanks to [@kravenoff42](https://github.com/kravenoff42) for the catch

## V 0.9.0 09-28-2018

- adds whitespace control for some control flow, comments, iterations and variables.

## V 0.8.7 11-14-2017

- miss spelled snippet fixed by [@KrisvanderMast](https://github.com/KrisvanderMast) on pull-request [#10](https://github.com/ginfuru/vscode-jekyll-snippets/pull/10)

## V 0.8.6 10-09-2017

- removes `.liquid` lang support
  - you should download [Liquid Languages Suport](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid) if you want need liquid snippets outside the support that Jekyll uses

## V 0.8.5 10-09-2017

- Added `.jekyll` lang support

## V 0.8.4 _(10-02-2017)_

- fixed image in readme

## V 0.8.3 _(10-02-2017)_

- update `extensionDependencies` to [Jekyll Syntax Support](https://marketplace.visualstudio.com/items?itemName=ginfuru.ginfuru-vscode-jekyll-syntax)

## V 0.8.2 _(09-06-2017)_

- added jsonify and fixed a few snippets

## V 0.8.1 _(05-21-2017)_

- updated readme to reflex the issue with formating repored from issue #8

## V 0.8.0 _(04-21-2017)_

- added HTML support due to odd behavior from other extensions not recognizing Liquid

## V 0.7.0 _(04-06-2017)_

- removed single quote from include snippet

## V 0.6.0 _(02-20-2017)_

- added markdown support requested from @Haroenv on issue #7

## V 0.5.0 _(02-18-2017)_

- merged the pull request from @thierrymichel

## V 0.4.0 _(01-23-2017)_

- updated the `CHANGELOG.md`
- added date variable

## V 0.3.2 _(01-23-2017)_

- Added `extensionDependencies` support to the package manifest
  - This will now prompt/inform you that the `Liquid Language Support` extension is needed and will ask you if you want to download it.

## V 0.3.1 _(1.4.17)_

- minor release to keep github release/tags in sync with `vsce minor` update

## V 0.3.0 _(1.4.17)_

- published to market place

## V 0.0.2

- preparing extension for publishing to market place

## V 0.0.1 _(12.30.16)_

- Initial release
  - added front-matter snippets
  - renamed prefixes to match atom editor
