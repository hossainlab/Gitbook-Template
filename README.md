# Gitbook Template

### Download & Install 
- Git Install 
```bahs
sudo apt-get install git 
```
- Check Version 
```bahs
git --version 

git version 2.7.4

```
- nodejs 
```bash 
node --version 

v11.15.0

```
- npm 
```bahs
npm --version

6.7.0
```
- gulp 
```bash 
npm install -g gulp

gulp --version

CLI version 3.9.1
```
- Gitbook 
```bash 

npm install -g gitbook-cli

gitbook --version

CLI version: 2.3.2
GitBook version: 3.2.3
```

### Creating Gitbook 
## `Step-1`
### Create a new repository on github.com  

## `Step-2`
### Create a bare clone of this repository
```bash
git clone --bare https://github.com/rebeccapeltz/gitbook-publishable-template.git
```
## `Step-3`
### Mirror-push to new repository
```bash
cd gitbook-publishable-template.git
```
```bash
git push --mirror https://github.com/useraccount/new-repository.git
```

## ` Step-4`
### Remove the temporary repository create above  
```bash
cd ..
```
```bash 
rm -rf old-repository.git
```
- Run 
```bash 
npm install
```
- Build Book 
```bash 
gulp
```
- Gitbook Plugin Install 
Select the gitbook plugin `book.json` file and run this command 
```bash 
gitbook install
```

### To Know More&Create Gitbook
[How To Create & Publish Gitbook](https://medium.com/@rebeccapeltz/publish-your-book-online-with-gitbook-fc0ce9b7f12)
