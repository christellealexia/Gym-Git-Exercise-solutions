# Git exercises

## Bundle 1
### Exercise 1
...bash
 git init
  502  git branch -m master main
  503  git status
  504  git add .
  505  git commit -m 'the first page'
  506  git remote add origin https://github.com/christellealexia/git-exercise.git
  507  git branch -M main
  508  git push
  509  git push --set-upstream origin main
  510  git checkout -b dev
  511  git checkout -b test
  512  git branch dev
  513  git checkout -
  514  git branch -D test
  ...bash
## Bundle 3
### Exercise 2
...bash
git checkout -b ft/faq-page
  511  git add .
  512  git commit -m 'changes made 
  513  git push
  514  git push --set-upstream orig
  515  git revert 366d970b64c66271b
  516  git revert 148002f19e8fa0e5d
  517  git checkout -b ft/home-page
  518  git checkout main
  519  git status
  520  git add .
  521  git commit -m 'changes made 
  522  git push
  523  git checkout ft/home-page-re
  524  git status
  525  git log
  526  git rebase main
  527  git log
  528  git status
  529  git add home.html
  530  git commit -m 'added another
  531  git push
  532   git push --set-upstream ori
  ...
  ## Bundle 4
  ### exercise 1
  ...bash
   git checkout main
  534  git remote add origin https:
  535  git branch -M main
  536  git remote add git-copy http
  537  git remote
  538  git status
  539  git add home.html
  540  git commit -m 'added a new l
  541  git push origin
  542  git push git-copy
  ...
  ### Exercise 2
  ...bash
   git checkout -b ft/footer
  544  git add .
  545  git commit -m 'footer page'
  546  git push
  547  git push --set-upstream orig
  548  git push --set-upstream orig
  549  git push --set-upstream orig
  550  git pull
  551  git commit -m 'other changes
  552  git add .
  553  git commit -m 'other changes
  554  git push
  555  git checkout main
  556  git checkout -b ft/squashing
  557  git merge --squash ft/footer
