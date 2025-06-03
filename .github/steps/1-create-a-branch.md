## Step 1: Create a branch

_Welcome to "Introduction to GitHub"! :wave:_

**What is GitHub?**: GitHub is a collaboration platform that uses _[Git](https://docs.github.com/get-started/quickstart/github-glossary#git)_ for versioning.
GitHub is a popular place to share and contribute to [open-source](https://docs.github.com/get-started/quickstart/github-glossary#open-source) software.

:tv: [Video: What is GitHub?](https://www.youtube.com/watch?v=pBy1zgt0XPc)

**What is a repository?**: A _[repository](https://docs.github.com/get-started/quickstart/github-glossary#repository)_ is a project containing files and folders.
A repository tracks versions of files and folders. For more information, see
"[About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)" from GitHub Docs.

**What is a branch?**: A _[branch](https://docs.github.com/en/get-started/quickstart/github-glossary#branch)_ is a parallel version of your repository.
By default, your repository has one branch named `main` and it is considered to be the definitive branch.
Creating additional branches allows you to copy the `main` branch of your repository and safely make any changes without disrupting the main project.
Many people use branches to work on specific features without affecting any other parts of the project.

Branches allow you to separate your work from the `main` branch.
In other words, everyone's work is safe while you contribute.
For more information, see "[About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)".

**What is a profile README?**: A _[profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)_
is essentially an "About me" section on your GitHub profile where you can share information about yourself with the community on GitHub.com.
GitHub shows your profile README at the top of your profile page. For more information, see "[Managing your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)".

![screenshot showing an example profile readme](https://github.com/user-attachments/assets/9425d1aa-04ba-459b-b89d-31fbae87c743)


### :keyboard: Activity: Clone the repository

Open your terminal or graphical Git client of your choice and clone this repository to your local machine.

```bash
git clone https://github.com/YOUR-REPOSITORY-URL.git
```

> **Note:** Replace `YOUR-REPOSITORY-URL` with the URL of your repository. You can find this URL in the **Code** on GitHub.

After cloning the repository, navigate to the cloned directory:

```bash
cd YOUR-REPOSITORY-NAME
```

### :keyboard: Creating a branch

The first step to contributing to a project is to create a branch. In this step, you will create a branch called `my-first-branch` to work on the project.

Continue using the terminal or git client you used to clone the repository. Create a new branch named `my-first-branch` by running the following command:

```bash
git checkout -b my-first-branch
```

> **Note:** The `-b` flag tells Git to create a new branch and switch to it immediately. To move to an existing branch, leave out the `-b` flag and just use `git checkout my-first-branch`.


### :keyboard: Pushing the branch to GitHub

Now that you created the branch, it exists only in your local copy of the repository. Next, push the branch to GitHub so that others can see it and you can continue working on it.

```bash
git push -u origin my-first-branch
```

> **Note:** You have likely used `git push` before, but the rest of the command might be new. The `-u` flag sets the upstream branch for your local branch, which means that future `git push` commands will automatically push to this branch on GitHub. `origin` is the default name for the remote repository you cloned from, and `my-first-branch` is the name of the branch you just created. Later, you can simply use `git push` to push changes to this branch.


### :tada: Wait for a minute and move to the next part of the exercise!

Now that your branch is pushed to GitHub, Mona should already be busy checking your work. Give her a moment and keep watch in the comments. You will see her respond with progress info and the next lesson.


<details>
<summary>Having trouble? 🤷</summary><br/>

If you don't get feedback, here are some things to check:
- Make sure your created the branch with the exact name `my-first-branch`. No prefixes or suffixes.

</details>