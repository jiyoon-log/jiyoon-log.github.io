---
title:  "[Github] Simple Github commands"

categories:
  - Github
tags:
  - Github
last_modified_at: 2022-08-18T08:06:00-05:00
---

In this post, it shows the simple Github commands. 

If you want to use the Github commands, you have to install the Github. (only Windows, Linux)

# Simple Github comands

```
git init
git add
git commit
```

# init

- preparing the Git local repository. 
- initializes the repository. 

So, you have to go to the directory for the Git local repository. 
And then, open the git bash or you can go with the command on git bash. 
```
$ git init
```
Then, it is ready to be the Git local repository.


# add
- moving changes in the current workign directory to the staging area.

Staging area is kind of a waiting place before commit.


## add options

  * adding <file/directory direction>
  ```
  $ git add <file/directory direction>
  ```

  * '.' : entire working directory 
  ```
  $ git add .
  ```


# commit
- saving the contents of the current staging area in the local repository and registered as a version.

```
$ git commit
```

## commit options

  * '-m' option : adding comments
  ```
  $ git commit -m "new version"
  ```

  * '--amend' option : changing the previous commit comments
  ```
  $ git commit --ammend -m "new version of previous version"
  ```

There are many other commands. 
I am trying to learn about it in next posts.

Thanks

[Reference]
* victolee: <https://victorydntmd.tistory.com/73>
* DaleSeo: <https://www.daleseo.com/git-add/>
