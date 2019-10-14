---
title: "Getting started with GitHub Desktop"
teaching: 20
exercises: 0
questions:
- "GitHub Desktop Set-up"
- "What are repositories and how are they created?"
- "What do `fetch`, `commit`, and `push` mean?"
- "How do I check the status of my repository?"
objectives:
- "create a git repository"
- "track changes to files using the git repository"
- "query the current status of the git repository"
keypoints:
- "Git repositories contain metadata about files under version control"
- "This metadata enables us to track changes to files over time"
- "Git uses a two-stage commit process. Changes to files must first be added to the staging area, then committed to the repository"
---

### Using GitHub Desktop

One of the main barriers to getting started with git is the language. Although some of the language used in git is 
fairly self-explanatory, other terms are not so clear. The best way to get to learn the language - which consists of a 
number of verbs such as `fetch`, `commit` and `push` - is by using it, which is what we will be doing during this 
lesson. These commands will be explained as we proceed from setting up a new version-controlled project to publishing our own website.

### GitHub Desktop Set-up

Before we can start tracking version, we must set-up our GitHub Desktop application with our GitHub account information. 

First, we will connect to our GitHub account using our username and password (if you didn't create a GitHub account before the lesson, you will need to do so now before you can proceed). 

1. Open GitHub Desktop. Click 'Sign in to GitHub.com'
2. Sign in using your GitHub username & password.
3. Update your user information if necessary.
4. Click 'Finish'.

You should now be logged in to your GitHub account. If you have any repositories associated with your account, you should see them listed in the left panel. 

### Creating a local repository

Now we are ready to create our first repository. We need to fill out some basic information about our repository before we can proceed.

- Name: The repository name. This will appear as the URL for the repo (it is best to not use spaces in the name).
- Description: Describe the contents of your repository.
- Local path: Destination on your machine to store the repository files. This will create a direcotry with the repository name. 
- README: Do you want to create a default README file for the repo? A README contains basic info about your repository and how to use the code or data you've uploaded.
- Git ignore: Choose default files to ignore. You can edit this file later.
- License: Choose to assign a license to your repository.

> ## Choosing a license
> Choosing a license is an important part of openly sharing your creative work online. For help in wading through the
> many types of open source licenses, please visit <https://choosealicense.com/>.
{: .callout}

Click 'Create Repository'. Now we've created our first local Git repository. 

### Publishing to GitHub

If we go the the directory we set as the 'local path' above, we should see a directory with our repo name. In this dorectory, we should see several files that we just created (README, .gitignore, license). 

In order to make our repo public, we need to click 'Publish repository'. This will publish our repo to GitHub.com and it will be listed under our list of repositories. 

### Making changes to a repository

Edit the README file
Create new files
Adding non-text files
	Images, PDFs, etc.
	Directories

> ## The README file
> It is good practice to add a README file to each project to give a brief overview of what the project is about. If you 
> put your README file in your repository's root directory, GitHub will recognize and automatically surface your README 
> to repository visitors
{: .callout}

### Commit & push changes to GitHub

Commit messages
See the Diff
Push changes to GitHub
View changes on GitHub

### Edit & Commit on GitHub.com

You can also edit files and commit changes using the GitHub.com site. You can only edit repos that you own or have been given edit permissions to. 

We will 'fetch' changes to the repo made through GitHub.com using GitHub Desktop. This will sync our local repository to match the version on GitHub.com. 

