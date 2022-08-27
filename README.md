# Problems:

## 1. When you have a existing git repo and you want to add that repo in your local folder for managing your git repo from there? (The solution here is using VS code)

### Prerequisites:
* Git
* VS CODE (Have to Log in using github account)
* Git Extension Pack (Open VS Code, Go to extensions, then install this extension)
### Performing the following steps:

> First you have to create a new folder from where you want to manage your git repo. Then, open your command prompt from there and use that command 
```
git clone "url_of_your_repository_"
```
(For example):

```
git clone https://github.com/gourab98/Github_Test.git
```

> After cloning that repo, Open that project with your VS code. Now you can make changes. Now you can push those changes to your remote repo. Now you can pull those changes from your remote repo. You can even do all kind of stafs from there. 

Some necessary commands for managing your git repo from there:

```
git add .
git commit -m "message"
git push
git pull
```
If you want to see the changes you made, you can use the command:

```
git status
```
