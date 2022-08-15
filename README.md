# file-add-into-git
How to folder and file push into github  
## you have open VS Code or cmd and open folder  
### To check git status  
```
git status
```  


1.

```
git init
```  

```
git add file name with extension
```  
or  
## 1.1 If you push folder then enter the following command on VS Code or cmd  


```
git add .
```  
## 3. git Commit:-  

```
git commit -m "File and folder insert intto github"
```  
## 4. For git Status:-  
```
git status
```  
## 5. To see git commit enter the following comand:-  
```
git log
```  
or  

### 5.1 
```
git log --oneline
```  
## 6. 
```
git status
```  

4.
```
git remote add origin https://github.com/repositorey name dite hobe
```  
5.
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

