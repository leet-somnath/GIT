```

```

---

* to see the changes -

  ```
   git status
  ```
* to check wheter the remote is added to current folder -

  ```
  git remote -v
  ```
* to add the folder to remote repostiry :(intilization)

  ```
  git init
  git remote add origin ssh-link
  git remote -v
  ```
* to check the content -

  ```
  ls
  ```

1. to clone the repostiry 🚀️: come to working directory then
   ```
   git clone ssh-link
   ```

* to add a file in the repositry

```
  git add file.txt
git commit -m "msg"
git push origin branch_name
```

* to get the history of your commits

```
git log
```

* To see at which branch we are :

```
git branch
```

* to create a branch

  ```git
  git checkout -b branchname
  ```
* to move to a branch

  ```
  git checkout branch_name
  ```
* to get the difference in main branch and other branch

  ```git
  git diff branchname
  ```
* some commands for resolvind conflicts

![1722238702388](images/GITINFO/1722238702388.png)

to pull :

```
git pull origin master
```
