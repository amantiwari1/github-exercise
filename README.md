# Github Demo - exercise

before start issue and exercise make sure installed required software

- git tools with git bash - [Git Install](https://www.atlassian.com/git/tutorials/install-git)
- use git bash in vscode tutorials here- [git bash in vscode](https://www.geeksforgeeks.org/how-to-integrate-git-bash-with-visual-studio-code/)

> Warning - do not change code or add folder or file in main branch instead use your own branch that tell you how to do in second step 1

## Clone it here

```shell
git clone https://github.com/amantiwari1/github-exercise.git
```

before start exercise make sure create issue click [here](https://github.com/amantiwari1/github-exercise/issues)
require -

- create new issue that what will you do in title and description.(Note - your choice to write - title and short description)
- Assignees - add yourself
- Labels - `good first issue`
- projects - `project development`

## let's start exercise in git

### First, create a new branch before you changes any code

create `branch` which allow you to create pull request after push

```shell
git branch csi/<YOUR-USERNAME>
```

go to branch (checkout) which you have created that

```shell
git checkout csi/<YOUR-USERNAME>
```

or

you can do create branch and go to branch (checkout) at the same time using

```
git checkout -b csi/<YOUR-USERNAME>
```

### Second, add your profile information

Create a markdown file in your main folder following the convention `<YOUR-USERNAME>.md`. Ex.

```filename
amantiwari1.md
```

Copy the into your file and fill the information with yours.

```
---
name: FULLNAME
institution: INSTITUTION-NAME
quote: YOUR-SENIOR-QUOTE
github_user: YOUR-GITHUB-USERNAME
---
```

### Third, push and submit your Pull Request

push your code to github website which you have created `<YOUR-USERNAME>.md`.

add stage file

```
git add `<YOUR-USERNAME>.md`
```

add commit file along with message

```
git commit -m "I created md file called `<YOUR-USERNAME>.md`"
```

finally, push code to github repo in gituhb org

```
git push origin csi/<YOUR-USERNAME>
```

Open click [here](https://github.com/amantiwari1/github-exercise)

as you see pop up above link and create pull request with title and description
required -

- reviewer - `amantiwari1`
- Assignees - add yourself
- Labels - `good first issue`

create it in button

go back to issue which you have created

- Linked pull requests - add which you have to created pull request

i will review your application, approve and merge your submission if everything is correct. Otherwise, you will get notified of the changes requested in the pull request comment section.

---

# Congratulations Completed Exercise - Happy hacking! :) 🎉🎉
