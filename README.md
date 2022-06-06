# Git  & GitHub
[Git Logo](C:/Users/Benny/Documents/Data30/repos/bennytking/GitHub_Logo_White.png)

## What is Git?
Git is the most popular version Control System that helps to **manage** project files
### Version Control
- _**Tracking** the changes of files, computer programs and other collection_
### Version control systems(VCS)
- _Particular set of tools which **aid a development team** in keeping track of every change made to the software_

## Git
- _Version Control Software_

## GitHub
- _Web Service_

## Repository creation overview

1. Create a Repository in GitHub
 ```touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:alexpchin/<reponame>.git
git push -u origin master```

2. Clone repository locally  ```git clone repository link```

3. Explore the cloned repository ```cd directory```

4. Make some changes and stage for commit ```readme.md```

5. Push local changes to remote repository
```git push <remote> <branch>```

6. Update local repository with Up-to-date remote repository
```git pull origin master```


7. Creating a branch
```git checkout -b ＜new-branch＞```
