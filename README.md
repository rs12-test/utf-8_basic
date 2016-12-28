This is a repository for testing git coding attributes in the following environment:

.gitattributes:
```
.gitattributes git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
<mask1> git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
<mask2> git-encoding=ISO8859-1 working-tree-encoding=IBM-1047
<mask3> git-encoding=UTF-8 working-tree-encoding=UTF-8
<mask4> git-encoding=BINARY working-tree-encoding=BINARY
```

The current content of .gitignore and .gitattributes files:

.gitignore
```
ignored_file*
!.gitignore
```

.gitattributes
```
.gitattributes git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1 export-ignore
.gitignore git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1 export-ignore
*.zip git-encoding=BINARY working-tree-encoding=BINARY export-ignore
*.jpg git-encoding=BINARY working-tree-encoding=BINARY export-ignore
*.png binary export-ignore
README.md export-ignore
*ascii* git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
*ebcdic* git-encoding=ISO8859-1 working-tree-encoding=IBM-1047
*untag* git-encoding=ISO8859-1 working-tree-encoding=IBM-1047
*utf-8* git-encoding=UTF-8 working-tree-encoding=UTF-8
*BINARY* git-encoding=BINARY working-tree-encoding=BINARY
*binary* binary
```
