# Collection of Git Commands
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Generic
**Undo your last commit**⋅⋅
`$ git reset --soft HEAD~`

**Undo "git commit --amend" done instead of "git commit"**⋅⋅
`$ git reset --soft HEAD@{1}`

## Git tags
**Create a tag**⋅⋅
`$ git tag -a v1.0.0 -m "v1.0.0"`

**Preview tags**⋅⋅
`$ git tag`

**Sharing tags**⋅⋅
`$ git push origin --tags`