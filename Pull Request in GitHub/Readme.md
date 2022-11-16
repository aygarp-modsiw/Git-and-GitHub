# How to create a pull request in GitHub?: A small guide to beginners in Hacktoberfest-2022

![Pull Request](https://miro.medium.com/max/720/1*renKnwJZGNCkMohfpUMeFA.jpeg)

It is really important to learn how to fork and clone a repository so you can make valid changes and later make a pull request. This article is for beginners who are confused as to how we can contribute to the open source.

You know the basic git commands which I have discussed in my article named — [Git: The Basics](https://github.com/aygarp-modsiw/Git-and-GitHub/tree/master/Git%20The%20Basics). However, contributing to other people’s repositories might be tricky if you’re new to it. So, let’s start with the way to fork the GitHub projects. For that reason, I have made this short guide for you.

First, visit the repository you want to fork and work on. You can see the option fork in the figure below: -

![Fork](https://miro.medium.com/max/720/1*xIxmLwP01E-QdRWm4kCaNw.jpeg)

This will create a copy of the above [portfolio](https://github.com/aygarp-modsiw/Portfolio) in your profile under your username as: -

#### `https://github.com/<user_name>/<repo_name>`

Now, we need to bring the repo to your local device with the help of the following command: -

#### `git clone https://github/<user_name>/<repo_name>`

This would download all the code, branches, and commits from the original repository to your device. Then, we need to do some things that are explained below: -

· Creating a new branch

#### `git checkout -b branch_name`

· Creating a new remote for the upstream repo with the command (Not always required)

#### `git remote add upstream <original repo_name>`

Then, you can make changes in the code and the usual push operations: -

#### `git add .`

#### `git commit -m "the changes"`

#### `git push -u origin branch_name`

After this, you can go to your GitHub repo you forked earlier and then click the “compare and pull request” button and you will be redirected to a screen where you can also add comments for the request and you can finally create a successful pull request which the maintainer will see and review to decide if they want to merge the changes.