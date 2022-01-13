# myproject

Learning Git

## Installation

https://github.com/bhuvanksmy/myproject.git

```bash
  291  cd /c
  292  ls
  293  cd Users/vtsth/Desktop/BhuvanaLearning/gitrepo/
  294  ls
  295  git --version
  296  mkdir myproject
  297  cd myproject
  298  git init
  299  git status
  300  git fetch
  302  git branch
  303  touch test.txt
  304  git status
  305  git add
  306  git add --help
  307  git add .
  308  git status
  309  git commit
  310  vi test.txt
  311  git status
  312  git commit -a
  313  git log
  314  git branch branch1
  315  git branch
  316  git checkout branch1
  317  ls
  318  vi test1.txt
  319  ls
  320  git status
  321  git add test1.txt
  322  git status
  323  git commit -m"new file created"
  324  git checkout -b branch2
  325  ls
  326  git branch
  327  git checkout master
  328  ls
  329  git merge branch1
  330  ls
  331  git branch
  332  git -d branch1
  333  git branch -d branch1
  334  git branch
  335  git checkout branch2
  336  vi test3.txt
  337  git checkout master
  338  vi test.txt
  339  git add -A
  340  git commit -m "test3.txt file created"
  341  git status
  
  354  git remote add origin https://github.com/bhuvanksmy/myproject.git

  357  git push --set-upstream origin master
  358  cd ..
  359  rm -fr myproject
  360  ls
  362  git clone https://github.com/bhuvanksmy/myproject.git
  363  ls
  364  git fetch

  366  cd myproject
  367  ls
  368  git branch
  369  git status
  370  git fetch
  371  git status
  372  git branch
  373  git pull
  374  git diff

  376  git diff origin master

  380  git checkout -b branch1
  381  git branch
  382  git push --set-upstream origin branch1
  383  git pull origin/master
  384  git pull master
  385  git pull origin master

```

## Usage

```git
git branch -r
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

