# file-add-into-github
How to folder and file push or upload into github  
## you have to install Git Bash  
## or open VS Code or cmd and open folder that you want to push into github   
---  
# Supose Repository Name salman-khan
## …or create a new repository on the command line 


```
echo "# salman-khan" >> README.md
```  

```
git init
```  
```
git add README.md
```  
```
git commit -m "first commit"
```  
```
git branch -M main
```  
```
git remote add origin https://github.com/md-ajij/salman-khan.git
```  
```
git push -u origin main
```  

# …or push an existing repository salman-khan from the command line
```
git remote add origin https://github.com/md-ajij/salman-khan.git
```  
```
git branch -M main
```  
```
git push -u origin main
```  
---  

### 1. To check git status  
```
git status
```  


## 2.

```
git init
```  
## 3.
```
git add file name with extension that you will push into github  
```  
# or  
## If you push folder then enter the following command on VS Code or cmd  


```
git add .
```  
## 4. git Commit:-  

```
git commit -m "File and folder insert intto github"
```  
## 5. For git Status:-  
```
git status
```  
## 6. To see git commit enter the following comand:-  
```
git log
```  
or  

### 6.1 
```
git log --oneline
```  
## 7. 
```
git status
```  

## 8. To add the file or folder into remote repository  

```
git remote add origin https://github.com/repositorey name dite hobe
```  
## 9.To push file and folder into Remote Repository  
```
git push -u origin master
```  

# Connection Between Local and Remote Repository   
## 1. You have to make a local folder or repository using your cmd like file-add-into-git
```
mkdir folder name 
```  
## 1.1 Example
```
mkdir file-add-into-git
```  
## 2. Now you have to move into the file-add-into-git by using the following comand  
```
cd file-add-into-git
```  
## 3. To check Whether the git is initialize or not  

```
git status
```  


## 4. To make git initialize 
```
git init
```  


## 5. Check remote connection:-  
```
git remote
```  
or  
```
git remote -v
```  


## 6. Make Connection:-  
```
git remote add name <REMOTE_URL>
```  
## Example of 6:  
```
git remote add origin http://github.com/md-ajjj/file-add-into-git.git
```  
## Note:- origin means http://github.com/md-ajjj/file-add-into-git.git  

## 5. Check remote connection:-  

```

git remote

```  

or  

```

git remote -v
```  
# Clone Remote Repository(copy):-
### You have to type on cmd is as folloes  
```
git clone http://github.com/md-ajjj/file-add-into-git.git
```  

