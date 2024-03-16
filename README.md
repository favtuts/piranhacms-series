# Deploying Piranha CMS to Azure series.
Contain source code for PiranhaCMS tutorials

# Part 1: Getting Started with Piranha CMS
In order to follow this tutorial that outlines how to deploy Piranha CMS to Azure, you'll need to meet the following prerequisites. Each of these resources are free or free to try for a limited time. If you simply want to run Piranha locally, install the .NET SDK and skip ahead to Part 2: Installing Piranha CMS Locally.

## Prerequisites
* [.NET SDK 8.0](https://dotnet.microsoft.com/download)
* [VS Code](https://code.visualstudio.com/)
* [GitHub account](https://github.com/signup)
* [Azure account](https://azure.microsoft.com/en-us/free/)

## Create a GitHub Repo
Before getting started with Piranha, you'll want to [create a GitHub repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/creating-a-new-repository) to store your code. This step is only required if you're planning to deploy your app using GitHub actions, but is definitely recommended. [Using version control](https://www.git-tower.com/learn/git/ebook/en/command-line/basics/why-use-version-control/) for your project allows you to keep snapshots of your code as it changes, enables collaboration and is a great way to backup your work.

I chose to create a private GitHub repo to store my Piranha project, and would recommend the same, however a public repo will work just fine too. If you decide to use a public repo, just make sure that you don't commit any sensitive data as it will be visible to anyone in the world. Nevertheless, once your repo is created, [clone it](https://github.com/git-guides/git-clone) to an easy-to-find path on your local machine. On my Mac, I like to use a code directory in my home folder, which is similar to the Documents folder on a Windows machine.

```
~/code/github/piranhacms
```

Using a tool like [GitHub Desktop](https://desktop.github.com/) can make interacting with GitHub easier, especially if you're unfamiliar with [git](https://learngitbranching.js.org/) or [version control](https://www.git-tower.com/learn/git/ebook/en/command-line/basics/what-is-version-control) in general.