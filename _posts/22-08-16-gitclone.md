---
title:  "[Github] Import GitHub project locally with clone command"

categories:
  - Github
tags:
  - Github
last_modified_at: 2022-08-16T08:06:00-05:00
---

In this post, it shows how to clone the Github project to the local. 

First, you have to know the URL of Github project that you want to clone. 

You can see the page like below when you go to the project page. 
Click the green button on the right side. 

![github_project](/assets/img/github_project_page.PNG)

And then, click the button that has two squares.

![github_button](/assets/img/github_button.PNG)


So, you just copy the URL of the repository in Github.

Next, move the project to the directory you want to clone.

![directory_pic](/assets/img/directory_pic.PNG)

Click the right button and "Git Bash Herer".
Git Bash terminal is poped.

```
$ git clone https://github.com/xxxxx/xxxxx.github.io.git
```
```
Cloning into 'xxxxx.github.io'...
remote: Enumerating objects: 17047, done.
remote: Counting objects: 100% (103/103), done.
remote: Compressing objects: 100% (86/86), done.
remote: Total 17047 (delta 20), reused 90 (delta 8), pack-reused 16944
Receiving objects: 100% (17047/17047), 44.74 MiB | 4.01 MiB/s, done.
Resolving deltas: 100% (10189/10189), done.
Updating files: 100% (753/753), done.

```

If the result comes out like above, the repository cloned into the local. 

![after_directory](/assets/img/after_directory.PNG)

Thank you!

[Reference]
* choiiis Devlog: <https://choiiis.github.io/git/how-to-clone-project/>
