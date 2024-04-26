# Git commands
## Création du repo

```
mkdir repo
cd repo
```
- Initialisation du repo:
```
git init
```
- Ajout du text dans le fichier:
```
echo "text" > file.txt
```
- Ajout du fichier et commit:
```
git add .
git commit -m "first commit"
```
- relier le repo local vers le repo distant:
```
git remote add origin <url_vers_repo_distant>
```
- pusher le code vers le repo distant:
```
git push
```
