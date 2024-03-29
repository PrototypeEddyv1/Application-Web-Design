# My data

## Student data
- Name: Eduardo Daniel Ruelas Zaragoza
- Registration number: 2850264
- Degree: Software Development Engineering
- Semester: 6th

## Subject data
- Subject name: Web Application Design
- Profesor's name: Erik Ezequiel Carrillo Moo

## Markdown utilities
The markdown is used to update a README file, this file contains all the information about the repository, some comments about the project, the goals and to organize the ideas.

## Tagging options with Markdown
- Use # To make a Header
- Use ## to make a secondary Header
- Use ### to make a side Header
- Use - to make a list
    - You can use numbers too (like 1., 2., 3.)
- Use > To make a Quote
- You can Also make text styles
    - **Bold you use** **
    - *Cursiva you use* *
    - ~To put a line in bewtween text you use~ ~
    - ***Cursiva and bold you use*** ***
    - <sub>to use subs you write</sub> sub and /sub (both with <>)
    - <sup>And Sup</sup> sup and /sup (both with <>)
- You can use `Site using` `
- And add links, use [] to make the text that's going to be clickeable and () to add the link, [MyPage](https://github.com/PrototypeEddyv1/Application-Web-Design#markdown-utilities)

## Git (Bash) commands
- **Check the Status of a local repository:** git status -s 
    > If an M in red appears aside of the document, that means it was modified
    > M in green means that a file added was modified
    
    > NOTE: Only appears the files that were added **BEFORE** a commit
- **Add individual files or globally:** git add nameFile
- **Add comments to the commit:** git commit -m "Put comentary here"
- **Upload your changes:** git push
- **Create, browse, and delete branches:**
    - **Create branch:** git branch nameOfBranch, and then add a file (with git add), do a commit, and then use "git push --set-upstream origin nameOfBranch"
    - **Check list of branches:** git branch -a
    - **Change Branch controll:** git checkout nameOfBranch
    - **Delete a Branch:** git branch --delete branchName
- **Roll back a repository to a specific commit:** git reset --hard numberOfChange (you can check with git log --oneline)