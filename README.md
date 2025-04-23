# Github-commands
### To create first time
```yaml
echo "# Github-commands" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/SapnaTiwari333/Github-commands.git
git push -u origin main
```
---
### To push existing repo
```yaml
git remote add origin https://github.com/SapnaTiwari333/Github-commands.git
git branch -M main
git push -u origin main
```
---
### To clone the reposistory

```yaml
git clone https://github.com/johndoe/nutritionix-app.git
```

---

### This will revert everything to the state before the merge was started.

```yaml
git merge --abort
```
---

### You need to pull the latest changes from the remote branch first, then push your changes:
```yaml
git pull origin main --rebase
```
---
### Stop tracking files without using .gitignore by using:

```yaml
find . -name "name of the file"
```
---

```yaml
git rm --cached <correct/path/to/firebase_options.dart
```
---

```yaml
git commit -m "Stop tracking Firebase-related files"
```
---

```yaml
git push origin main
```
