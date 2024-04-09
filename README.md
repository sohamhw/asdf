# Template Repository Guide

This guide walks you through the process of cloning, setting up, and collaborating on a GitHub repository based on this template.

## Cloning the Repository

1. **Start with the Template:** Click **Use Template** in the top right corner of this repository page. Ensure the repository is public to facilitate collaboration.

   ![Screenshot 2024-04-05 123446](https://github.com/InteracionLabWorkshopTeam/repository-template/assets/74628574/42081397-92eb-43df-a131-9b95dc80bdd3)

2. **Prepare Your Environment:**
   - Ensure you have the correct version of Git installed on your computer. If not follow [this](https://github.com/InteracionLabWorkshopTeam/installation-guide) manual and [download Git here](https://git-scm.com/downloads).
   - Open Git Bash or Terminal in a folder of your choice:
     - **Windows:** Open the folder in explorer, right-click, select *Show more options*, then *Git Bash here*.
     - **Mac:** Open the folder in Finder, control-click the path bar, choose *Open in Terminal*.

3. **Clone the Repository:** Use the command `git clone <your repository url>` to clone your new repository to your computer.

---

## Setting Up Your Local Repository

1. **Create a File:** Inside the cloned repository folder, create a `filename.txt` file and save it.
2. **Commit and Push:**
   - Open Git Bash/Terminal again.
   - Stage your new file with `git add filename.txt`.
   - Commit your changes using `git commit -m 'your commit comment'`.
   - Push your changes with `git push`.

Refreshing your GitHub repository page should now show the `filename.txt` file.

---

## Collaboration and Branching

### Initial Setup

1. **Collaboration:** Pair up in groups of 2 or 3. Add each other as collaborators under Settings > Collaborators and Teams > Add People, granting write access.

![Screenshot 2024-04-09 160341](https://github.com/InteracionLabWorkshopTeam/repository-template/assets/74628574/06056b18-42fa-422d-8727-8527263142bc)

### Creating a Branch

1. **Branch Out:** Now that you have access to each other's repositories, it's time to create a branch. A branch allows you to make changes to your code without affecting the main branch directly.

2. **Development:** Clone the branch, commit, and push changes as you would with the main repository. This method allows simultaneous development and careful integration of changes.

   ![Git Branching](https://github.com/InteracionLabWorkshopTeam/repository-template/assets/74628574/33e9961d-893e-45ac-8e8f-e050dda9a492)

Branching is essential for collaborative development, allowing for safe testing and gradual integration of new features or changes.

## Merging Changes

After collaborating and making changes on your branch, the next step is to merge these changes back into the main branch. This process combines the progress made in different branches, allowing the team to consolidate their work.

### Reviewing Changes

1. **Pull Request:** One team member should initiate a pull request on GitHub. This is a formal way of saying, "I have completed my changes and would like them to be reviewed and merged into the main branch."

2. **Code Review:** Team members review the changes. This review process can include:
   - Reading the modified story in `filename.txt` to ensure it flows well with the original content.
   - Checking for spelling and grammatical errors.
   - Ensuring that the changes align with the project's goals.

### Merging
>
1. **Approve the Pull Request:** Once the team agrees that the changes are ready, they can approve the pull request. This is often done by someone other than the author of the changes to ensure impartiality.

2. **Resolve Conflicts:** If there are any conflicts (i.e., the same lines of the file have been changed in both the main branch and the branch being merged), they must be resolved. This can be done directly on GitHub or locally by checking out the branch, resolving the conflicts, and pushing the resolved version.

3. **Merge:** With conflicts resolved and approval granted, the final step is to merge the branch into the main branch. GitHub provides a "Merge" button that can be clicked to automatically perform this action once all conditions are met.

## Overview and cheatsheets

Git terminology: https://www.pluralsight.com/resources/blog/cloud/git-terms-explained <br>
Creating a repo on github: https://docs.github.com/en/repositories/creating-and-managing-repositories/quickstart-for-repositories <br>
Creating a repo directly in vscode: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git <br>

Connecting with github through ssh: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

## Celebrate Your Collaboration

After merging, take a moment to celebrate your teamwork and the story you've collectively enhanced in `filename.txt`. This process of branching, reviewing, and merging is a cornerstone of collaborative development, allowing multiple people to work on different aspects 
