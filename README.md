# BHlab_exercise1
A short exercise to clone this repo and modify the file locally


***

### git key commands:

Only do this once, the first time you need to access this repository. This will clone the repository so you can access it locally

```{r}
$ git clone https://github.com/marta-vidalgarcia/BHlab_exercise1.git
```

<br>

Go inside the folder.

```{r}
$ cd BHlab_exercise1 
```

<br>

You can then see that there is a .git object here

```{r}
$ ls -la
```

<br>

This gives an overview of the local working directory and the staging area. You will see whether there are "Untracked files", any staged changes, whether your local repo is up to date with the remote, etc.

```{r}
$ git status 
```

<br>

***Pull, pull, pull.*** Pull each single time before commiting & pushing any of your changes, even if you are the sole contributor to your repo. You might have worked on it from another computer, so pull all new changes before adding your new work.
```{r}
$ git pull # every single time before adding any new files and/or files with changes
```

<br>

Add the files you have been working on (they will appear as untracked with "$ git status")

```{r}
$ git add <my file>
```

<br>

Commit your changes. Give an informative description. We don't want a two word commit (e.g. added file), or a paragraph

```{r}
$ git commit -m "I added my file and I give a description of what I changed or added"
```

<br>

Finally push your changes to the remote repo!

```{r}
$ git push
```

<br>

Great job!!!
