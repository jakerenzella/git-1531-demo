# ammending a git commit because you made a typo:
1. `git commit -m "problematic commit message`
2. `git commit --ammend` and edit the message
3. `git push`, or, `git push --force` if you pushed the problematic commit and nothing else afterwards.

# ammending a commit may bring up an editor, you can change this...
`git config --global core.editor "code --wait"`
`git config --global core.editor "nano"`

# gitignore.io
`https://www.toptal.com/developers/gitignore`
