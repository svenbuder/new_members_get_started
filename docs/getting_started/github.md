# Getting Started with GitHub

## Table of Contents
- [Prerequisites](#prerequisites)
- [Using GitHub](#using-github)
  - [Apple](#apple)
  - [Windows](#windows)
- [Syncing a Git Repository to Read the Docs](#syncing-a-git-repository-to-read-the-docs)

## Prerequisites
Before getting started, make sure you have the following:

- A GitHub account (create one at https://github.com if you don't have it already)
- Git installed on your computer (download from https://git-scm.com/downloads)

## Using GitHub

You can either download (clone) and existing repository, or create and upload your own.

### Cloning existing repository from the github website

1. Open Terminal (on your Apple device) or Command Prompt or Git Bash (on your Windows device).
2. Navigate to the directory where you want to clone the GitHub repository using the `cd` command. For example, `cd Documents` to navigate to the "Documents" directory.
3. Clone the repository by running the following command in Terminal/Command Prompt:

```
git clone <repository_url>
```

Replace `<repository_url>` with the URL of the GitHub repository you want to clone, e.g. `https://github.com/svenbuder/new_members_get_started.git`.

### Upload/Create repository from a local directory

1. Create a new repository on the [GitHub website](https://github.com). You can do this by going to the GitHub website, logging in to your account, and clicking on the "New" button to create a new repository. Give it a name `project_name` and configure any additional settings as needed.
2. If you create a 
``` bash
echo "# project_name" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/svenbuder/project_name.git
git push -u origin main
```

After executing these commands, your local directory will be linked to the GitHub repository, and you'll be able to push and pull changes between the local and remote repositories using Git commands.

## Syncing a Git Repository to Read the Docs
1. Sign in to Read the Docs at https://readthedocs.org using your GitHub account.
2. Click on the "Import a Project" button.
3. Select the GitHub repository you want to sync from the list.
4. Choose the appropriate settings for your project, such as version control type and documentation type.
5. Click on the "Build" button to start the initial documentation build.
6. Once the build is complete, your documentation will be available on Read the Docs.