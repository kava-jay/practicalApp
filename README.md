## Git Practical


Branch:-
Main(Master)
Login
Feature

Steps:

1. Pull and Merge difference
- Make example of pull request and two branch merge event.
- Created one login branch into master branch and then merge login branch with master branch using pull request


2. Rebase
- Try to rebase feature branch with master branch 
- Created one new feature1 branch in that created f1.txt and rebase with master file m1.txt and  m2.txt.
- Here m1.txt and m2.txt belogs to main and f1.txt belogs to fatures1(feature branch)
  git rebase master


3. Change commit message
- Commit push on commit in feature branch and then change commit message
- Goto login branch and change commit "first commit" to "new commit message"


4. cherry pick
- Pick some commits from feature branch to master branch
- In login branch we added 2 file dummy1.txt and dummy2.txt.
- Now we want to merge only dummy1.txt into main branch so we perform cherry-pick on master 
  branch 
- Finally dummy.txt only one file is added in main branch not dummy2.txt.


5. Drop commit
- Remove some commit from feature branch.
- GO to feature1 branch
- here last commit is "added f1.txt file in features1 branch"
- Remove this commit using git reset --hard HEAD~1
- f1.txt file commit is droped.
