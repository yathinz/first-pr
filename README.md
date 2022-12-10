# First Pull Request

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository


<img align="right" width="300" src="https://user-images.githubusercontent.com/93030904/206855000-eb42c8bf-aa56-4f05-aa82-bb8a8fddae81.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.


<img align="right" width="300" src="https://user-images.githubusercontent.com/93030904/206855026-df01a4e1-9873-42a0-b9fc-828302cfb125.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/first-pr.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

For example:

```
git switch -c add-alonzo-church
```

## Make necessary changes and commit those changes

Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.


<img align="right" width="450" src="https://user-images.githubusercontent.com/93030904/206855068-4b50d277-20dd-48f7-a141-412e2e4be919.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add Contributors.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add your-name to Contributors list"
```

replacing `your-name` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.



<img style="float: right;" src="https://user-images.githubusercontent.com/93030904/206855336-9c00752e-d9b3-42e7-a9c4-52a64ee52088.png" alt="create a pull request" />

Now submit the pull request.


<img style="float: right;" src="https://user-images.githubusercontent.com/93030904/206855111-1e009ef7-e6a2-4a30-9ff4-249aed7a8ae6.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.
