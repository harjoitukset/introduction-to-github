## Step 2: Commit a file

_You created a branch! :tada:_

Creating a branch allows you to edit your project without changing the `main` branch. Now that you have a branch, it’s time to create a file and make your first commit!

**What is a commit?**: A _[commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ is a set of changes to the files and folders in your project. A commit exists in a branch. For more information, see "[About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)".

### :keyboard: Activity: Your first commit

The following steps will guide you through the process of committing a change on GitHub. A commit records changes to the project such as adding/removing/renaming files and modifying file content. For this exercise, committing a change will be adding a new file to your new branch.

> [!NOTE]
> `.md` is a file extension that creates a Markdown file. You can learn more about Markdown by visiting "[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)" in our docs or by taking the "[Communicating using Markdown](https://github.com/skills/communicate-using-markdown)" Skills Exercise.

1. On your command line, make sure you are in the root folder of this repository. You should see the `.github` folder and the `README.md` file.

   ```bash
   # Check your current directory
   pwd

   # List the files in the current directory (Unix/Linux/macOS)
   ls -la

   # List the files in the current directory (Windows)
   dir    # Windows
   ```

2. When you are in the correct folder, make sure that you are working on the `my-first-branch` branch. You can check this by running:

   ```bash
   git branch
   ```

   If you see `my-first-branch` with an asterisk next to it, you are on the right branch. If not, switch to it using:

   ```bash
   git checkout my-first-branch
   ```

3. Now, let’s create a new file called `PROFILE.md` in the root folder of your repository. You can do this using your favorite code or text editor. The contents of the file should be as follows:

   ```md
   Welcome to my GitHub profile!
   ```

4. After creating the file, you can check that it exists by running:

   ```bash
   git status
   ```

   You should see `PROFILE.md` listed among the files, but it is not yet tracked by Git.

5. Add the new file to the staging area by running:

   ```bash
   git add PROFILE.md
   ```

   This command tells Git that you want to include the changes in `PROFILE.md` in the staging area, where changes are prepared to be committed.

6. Now, `git status` should show that `PROFILE.md` is ready to be committed.

   ```bash
   git status
   ```

   Create a new commit and give it a descriptive message:

   ```bash
   git commit -m "Added profile readme"
   ```

8. Finally, push your changes to the `my-first-branch` branch on GitHub:

   ```bash
   git push

   # no need to specify the remote or branch in the command, as you set the upstream branch earlier
   ```

   This command uploads your local commits to the remote repository on GitHub.

9. Now that you've added a file and pushed it to GitHub, Mona should already be busy checking your work. Give her a moment and keep watch in the comments. You will see her respond with progress info and the next lesson.


<details>
<summary>Having trouble? 🤷</summary><br/>

If you don't get feedback, here are some things to check:
- Make sure you are on the `my-first-branch` branch.
- Ensure the `PROFILE.md` file is created and in the root folder.

</details>
