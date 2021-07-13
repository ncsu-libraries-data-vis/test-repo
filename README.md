# Using Git and GitHub

This document provides a workflow for creating and contributing to a new GitHub repository, specifically a repository in the [NC State Libraries Data & Vis Organization](https://github.com/ncsu-libraries-data-vis), using the Git command line tool or the application GitHub Desktop.

## Requirements

* A GitHub account (If you do not have an account, create one through the [join GitHub page](https://github.com/join)).
* Membership to the [NC State Libraries Data & Vis Organization](https://github.com/ncsu-libraries-data-vis) (Email Walt to receive an invitation).
* Git ([Git Download page](https://git-scm.com/downloads)) **OR** GitHub Desktop ([GitHub Desktop download page](https://desktop.github.com/)).

## Step 1: Create a new repository on GitHub

The following instructions walk through the process of creating a new GitHub repository in the [NC State Libraries Data & Vis Organization](https://github.com/ncsu-libraries-data-vis). If you want to contribute to an existing repository you can skip to Step 2a, or Step 2b for instructions on using Git in the terminal or GitHub Desktop.

1. In a browser, navigate to the [NC State Libraries Data & Vis Organization](https://github.com/ncsu-libraries-data-vis).
1. Click the button labeled *New* in the upper-right corner.
1. On the **Create a new repository page** the default owner should be set to *ncsu-libraries-data-vis*.
1. Create a new repository name:
    1. The name should be short (approximately five words or less) and descriptive.
    1. Separate each word with a dash (-).
        > For example:
        >
        > The workshop "An Introduction to Programming with Python" has the repository name *introduction-to-programming-with-python*.
1. Add a short description of the repository (approximately one to two sentences). 
    > For example:
    >
    > The workshop "An Introduction to Programming with Python" has the description *These materials introduce fundamental concepts of programming through the Python programming language.*
1. In most cases, the repository should be set to public–anyone on the internet can see the repository but cannot automatically commit.
1. Initialize the new repository with:
    1. A [README file](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-readmes) (This file will eventually contain an in depth description of the repository materials.)
    1. A [License file](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/licensing-a-repository) (From the license options select [MIT License](https://choosealicense.com/licenses/mit/). The copyright attribution on line 3 of this file, `Copyright (c) 2021 NC State Libraries Data & Vis`, should eventually be edited to: `Copyright (c) 2021 NC State University`)
    1. *If using a specific language/tool*, a [.gitignore file](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files) using the appropriate provided template.

        > For example:
        >
        > The workshop "An Introduction to Programming with Python" uses the Python template.

        If there is not an appropriate template for the new repository, skip creating a .gitignore file. A .gitignore files should eventually be created in the root folder of the repository. A good base .gitignore configuration example is available in ["Some common .gitignore configurations"](https://gist.github.com/octocat/9257657).
1. Click the button labeled *Create repository*

## Step 2a: Using Git from the terminal

## Step 2b: Using GitHub Desktop
