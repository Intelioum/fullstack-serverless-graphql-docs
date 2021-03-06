---
path: /creating-frontend-repo
title: Creating the Frontend Repo with Vue CLI
tag: frontend
date: 2020-05-18T18:06:34.032Z
part: Setup frontend
chapter: Vue cli
postnumber: 21
framework: vue
---

In this section we will start building out the frontend of the Lunar Tour app with VueJS. First we will need to create the repo on [Github](https://github.com).

First go to Github and create new repo:

![](/uploads/github_step.png)

Now that we have it created. We need to install the [Vue CLI](https://cli.vuejs.org/). It will allow us to scaffold the project. In your terminal run the following:

```bash
$ yarn global add @vue/cli
```

Once it is installed run the following:

```bash
$ vue create lunar-tour-frontend
```

Select the default option:

![](/uploads/step_1.png)

Select the Babel, Router & Linter options.

![](/uploads/step_2.png)

Select Y for the history:

![](/uploads/step_3.png)

Sit back and let the CLI do the work:

![](/uploads/step_5.png)

Now change into the directory and start the app:

```bash
$ yarn serve
```

If you go to `localhost:8080` your app should be visible.

Now we need to commit this to our repo. Initialize the local directory as a Git repository:

```bash
$ git init
```

Add the files in your new local repository. This stages them for the first commit:

```bash
$ git add .
```

Commit the files that you've staged in your local repository:

```bash
$ git add .
```

In Terminal,[add the URL for the remote repository](https://help.github.com/en/articles/adding-a-remote) where your local repository will be pushed:

```bash
$ git remote add origin remote repository URL
# Sets the new remote

$ git remote -v
# Verifies the new remote URL
```

[Push the changes](https://help.github.com/en/articles/pushing-commits-to-a-remote-repository) in your local repository to GitHub:

```bash
$ git push -u origin master
```

Now all our code is synced with Github.

Lastly, create a folder `assets` in the `src` directory and copy all the images in this [Google Driver folder](https://drive.google.com/drive/folders/178c-yMzNPj013dpEwkcDAQHArxjTa1HZ?usp=sharing). These are all the icons and images we will need for the project.
