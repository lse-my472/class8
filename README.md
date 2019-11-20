# Instructions for Class Work, Week 8

As in week 5, in this class session, we will be working during each class interactively and in groups.  Each student will select a topic on which to focus, and form into groups of 4-5 around each topic. After working for 25-30 minutes collaboratively on a topic, a person (or several) from each group will present the solution to the rest of the class, in 3-4 minutes max each.

## Before you start

You will need to _clone_ this repository on a local machine, as that is where your work will occur.  Each student in MY472 has already been invited to join the "Students 2019" group for the GitHub _organization_ **lse-my472**, and this group has been assigned authoring (read, write, management) permissions to the **class8** repository.  If you have not already accepted an invitation to join this group, please do so now.  If you did not receive an invitation for some reason, please contact Sarah or Jinny and they will invite you.

## Cloning the repo locally

To clone the repository locally, the easiest method is through RStudio, which also will create an RStudio "project" for this repo.  You can do this from the Projects button in the upper right of your RStudio window, and select New Project -> From Version Control -> Git.   Put the URL of this repository into the source input box: https://github.com/lse-my472/class8.git, and press Enter.  This will clone the remote repository and create an RStudio project on your local drive.

## Create a branch for your work

One person in your group should create a new branch for your particular work, which should be named to reflect the topic.  For work on the loops task, you should create a new branch called `class8-task-loops`.  This can be done from the branch icon next to Git in the Git tab of RStudio, which will also push the branch to the remote.  Because there are two classes, please don't forget to add the name of your class before the task name, for the branch!

## Edit the file

For this example, for instance, you would edit the file `task-loops.Rmd`, while working in your branch locally.  Your group should work on this until you are happy with the solution.

## Push the changed file to the remote branch

Once the file has been changed, commit those changes locally, and then push them to the remote.

## Issue a pull request from GitHub

You can do this from the main repository page, either next to your branch from the list of branches, or from a prompt next to the most recent commit on the main repository page.

Once the "PR" has been submitted, one of the class instructors will be able to review it.  (These will be accepted only after Friday however, when the second group has completed its work!)

# Presenting the work

On the lab main computer, which is hooked up to the projector, we will have also cloned the repository from RStudio.  Once your branch is updated and pushed with your group's solution, we will be able to pull the remote to the local projector-connected machine, and then execute the code.  This will be how each group presents its solution, by walking through the Rmd code.
