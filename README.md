This is a repository for testing git coding attributes in the following environment:

.gitattributes:
```
.gitattributes git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
<mask1> git-encoding=ISO8859-1 working-tree-encoding=<encoding1>
<mask2> git-encoding=ISO8859-1 working-tree-encoding=<encoding2>
<mask3> git-encoding=ISO8859-1 working-tree-encoding=<encoding3>
```

The current content of .gitignore and .gitattributes files:

.gitignore
```
ignored_file*
!.gitignore
```

.gitattributes
```
.gitattributes git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
.gitignore git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
*ascii* git-encoding=ISO8859-1 working-tree-encoding=ISO8859-1
*ebcdic* git-encoding=ISO8859-1 working-tree-encoding=IBM-1047
*untag* git-encoding=ISO8859-1 working-tree-encoding=IBM-1047
*utf-8* git-encoding=ISO8859-1 working-tree-encoding=UTF-8
```
