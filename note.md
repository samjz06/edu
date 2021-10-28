### tell git who you are (globally)
`git config gloabl user.email`
`git config gloabl user.name`

### initialze a repo
`git init`
`git config user.email`
`git config user.name`

### maintain an existing repo
`git clone`: do not clone to a repo (folder with .git)

### delete
`rm -rf *`
`rm -rf a`

### add
`git status`: this will see the status of files within the repo(untracked, to be committed).
`git add`: this will add 'untracked' file to be 'to be committed'.

### commit
`git commit -m 'message'`

### git ignore
`*.txt`: ignore all txt file
`!a.txt`: ignore all but 'a.txt'
`/vendor`: ignore entire folder 
`/vendor/*.php`: ignore '.php' in '/vendor' but not other subfolders under 'vendor'
`/vendor/**/*.php`: ignore all '.php' as well as those in subfolders.

### delete revisit
