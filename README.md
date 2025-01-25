# Application-Web-Design
## About me
**name:** Daniel Kzrysztof Mansur Pedraza

**registration number:** 3054347

**Degree:** Software Engineering

**Semester:** 6th

## About this class
**name of the subject:** Application web design.

**name of the teacher:** Mario Eduardo Rodriguez Palafox

## 

# ASSIGNMENT HW 1

## MarkDown tagging options.
there are various options since it is based on html
first the headings.

# THIS IS A TITLE
you start the line with the character "#" and the you leave a space and write the title.

for each # the title is smaller 

## Emphasis

there are 2 ways to make an emphasis.

italics _like this_ 

bold **like this**

or even both *__LIKE THIS__*

## Lists

### Unordered

* Tomtato
* Potato
* Beans
* Cake ingredients
    * Milk
    * Flour
    * Eggs
    * Sugar

### Ordered

1. Data structues and algorithms
2. Data bases
3. Operative systems
    1. system calls
    2. processes

## Images

![This is an alt text.](/image/sample.webp "This is a sample image.")

## Links

The website that helped me with this [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> If the world was ending, I would move to Cincinnati, because everything there happens 20 years later. ~Mark Twain 

## Tables

| html          | md            |
| ------------- |:-------------:|
| h1, h2, h3... | #, ##, ###... |
| bold          | ** text **    |
| italics       | _ text _      |
| ul            | start the list with the * symbol each bullet point|
| ol            | start the list with a number each point     |
| img           | write the link after the ![]    |
| link          | write the link after the []     |


# write a code block

```
#include <stdio.h>
int main() {
   // printf() displays the string inside quotation
   printf("Hello, World!");
   return 0;
}


```

# write code inline

you can use `gcc` to manage your C code and make various actions



## Git commands.

Add another section where you will list the commands used in git to do the following:
* Check the status of a local repository. 

you can use the command `git status` to check all the files that present any change

* Add individual files or globally.
    * Individual `git add <filename>`
    * All   `git add .`

* Add comments to the commit.

when you add a commit you need to add the flag `-m` and then add between quotes
like this `git commit -m "first commit"`

* Upload your changes to the remote repository.

you add the repository like this `git add origin <your repo link>`
and then you use the `git push origin <name of your branch>`

* Create, browse, and delete branches.

create: `git branch <branch name>`

switch: `git checkout <branch name>`

view all branches: `git branch`

delete: `git branch -d <branch name>`

* Roll back a repository to a specific commit.

view the history: `git log`

roll back and save changes: `git reset <commit hash>`

roll back to an delete current changes: `git reset --hard <commit hash>`