## GitHub SSH
```
$ ssh-keygen -t rsa -b 4096 -C "peppapig13132@gmail.com"
```

```
# C:\Users\Admin\.ssh\config

#peppapig13132 account
Host peppapig13132.github.com
  HostName github.com
  User git
  IdentityFile ~/.ssh/peppapig13132
```

```
git@peppapig13132.github.com:peppapig13132/repository_name.git
```
## Last Commit Update
```
$ git commit --amend -m "new commit"
```
```
$ git push --force origin main
```
