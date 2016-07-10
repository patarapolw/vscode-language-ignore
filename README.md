# Ignore files Package for VS Code

[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/ldez/vscode-language-ignore/blob/master/LICENSE.md)

Adds syntax highlighting to 'ignore' files.


## Supported files

- `.gitignore`: references [gitignore](https://git-scm.com/docs/gitignore) and [Ignoring-Files](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#Ignoring-Files)
- `.npmignore`: works just like a `.gitignore` [references](https://docs.npmjs.com/misc/developers#keeping-files-out-of-your-package)
- `.dockerignore` : works just like a `.gitignore` [references](https://docs.docker.com/engine/reference/builder/#dockerignore-file)
- `.coffeelintignore`: works just like a `.gitignore`.
- `.slugignore`: does not support negated `!` patterns. [Heroku - Slug Compiler](https://devcenter.heroku.com/articles/slug-compiler#ignoring-files-with-slugignore)
- `.atomignore`: works just like a `.gitignore`. [tree-ignore](https://atom.io/packages/tree-ignore)
- `.hgignore`: references [hgignore](https://www.mercurial-scm.org/wiki/.hgignore) (currently only glop patterns)
- `.vscodeignore`: works just like a `.gitignore` [references](https://code.visualstudio.com/docs/tools/vscecli#_advance-usage)
