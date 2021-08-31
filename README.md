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
    1. *If the repository will consist of software*, a [License file](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/licensing-a-repository) (From the license options select [MIT License](https://choosealicense.com/licenses/mit/). The copyright attribution on line 3 of this file, `Copyright (c) 2021 NC State Libraries Data & Vis`, should eventually be edited to: `Copyright (c) 2021 NC State University`)

        If the new repository will consist of instructional materials, skip creating a LICENSE file. Instead, manually create a LICENSE file and add copy the [Creative Commons Attribution 4.0 International](https://choosealicense.com/licenses/cc-by-4.0/) license language contained in [the LICENSE file within this repository](https://github.com/ncsu-libraries-data-vis/using-git-and-github/blob/main/LICENSE).

    1. *If using a specific language/tool*, a [.gitignore file](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files) using the appropriate provided template.

        > For example:
        >
        > The workshop "An Introduction to Programming with Python" uses the Python template.

        If there is not an appropriate template for the new repository, skip creating a .gitignore file. A .gitignore files should eventually be created in the root folder of the repository. A good base .gitignore configuration example is available in ["Some common .gitignore configurations"](https://gist.github.com/octocat/9257657). You can also explore [this collection of .gitignore templates](https://github.com/github/gitignore) for a relevant template for your materials (e.g., there is a [template for Microsoft Office](https://github.com/github/gitignore/blob/master/Global/MicrosoftOffice.gitignore) for PowerPoint, Excel, etc.).

1. Click the button labeled *Create repository*

## Step 2a: Using Git from the terminal

## Step 2b: Using GitHub Desktop

### Adding new materials

1. In Github, navigate to your repository.
1. Click on the green "Code" button in the top right.
1. Select "Open with GitHub Desktop."
1. In the GitHub Desktop app, select a local path.
    > You are creating a copy of the repository on your machine to edit, so choose a local path that makes sense for you (for example: a folder that stores all of your GitHub repositories).
1. Click the blue "Clone" button.
1. Access the instruction materials on your computer.
    > If you are transferring materials from a shared Drive, this may mean downloading the entire folder for the workshop materials and unzipping them.
1. Move the folder of downloaded materials into the folder you chose earlier for your local path. This will move the materials into your local copy of the repository.
1. In GitHub desktop, you should now see in the left pane that there are changed files (the ones you just moved).
1. Commit to the main branch
    1. At the bottom left, write a short title for your commit and an optional description.
    1. Click on the blue "Commit to main" button
1. Push commits to the origin.
    1. At the top toolbar, the right-most box should now give you the option to "Push origin," click on that box to push.
    2. Alternatively, in the right pane, you should now see the option to push commits to the origin remote.
1. Click the blue "Push origin" button.

### Editing existing materials

1. Before editing, fetch the most recent changes and check to make sure you are in the right branch.
    1. Check your branch and create new branches in the middle dropdown of the UI called "Cuurent branch."
    1. Click the rightmost box in the top toolbar that says "Fetch origin"
    > This will make your local copy match the one in the GitHub repository. If you have changes that you have not pushed, this may cause a conflict.
1. Make your edits as usual and save to the same file.
1. In GitHub desktop, you should now see in the left pane that there are changed files (the ones you just moved).
1. Commit to the main branch
    1. At the bottom left, write a short title for your commit and an optional description.
    1. Click on the blue "Commit to main" button
1. Push commits to the origin.
    1. At the top toolbar, the right-most box should now give you the option to "Push origin," click on that box to push.
    2. Alternatively, in the right pane, you should now see the option to push commits to the origin remote.
1. Click the blue "Push origin" button.
