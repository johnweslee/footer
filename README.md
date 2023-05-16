# Footer
---

## Quick setup
http : [https://github.com/johnweslee/footer.git](https://github.com/johnweslee/footer.git)

ssh : [git@github.com:johnweslee/footer.git](git@github.com:johnweslee/footer.git)

---
## Create new repository on the command line
```
echo "# footer" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/johnweslee/footer.git
git push -u origin master
```
---
## push an existing repositiry from the command line
```
git remote add origin https://github.com/johnweslee/footer.git
git branch -M master
git push -u origin master
```