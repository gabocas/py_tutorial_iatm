```bash
cd directory_where_your_repository_will_be
mkdir py_tutorial_iatm
cd py_tutorial_iatm
git init
git status
touch README.md
git status
git add README.md
git status
git commit -m "Add README file"
git log
git remote add origin https://github.com/gabocas/py_tutorial_iatm.git
git push -u origin master
git commit -m "README file updated"
git branch workshop
git checkout workshop
git rm '*.md'
git commit -m "README file removed"
git checkout master
git merge workshop
git branch -d workshop
git push
git clone https://github.com/gabocas/empty.git
```