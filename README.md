# Git and GitHub Workshop - Cohort 11 Names Collection Exercise

Welcome to the Git and GitHub Workshop Cohort 11 Names Collection Exercise!

## Overview

This workshop aims to teach participants the basics of using Git and GitHub for version control and collaborative development. In this exercise, participants will collaborate on a Python script to collect names from each individual and eventually create a list of names for everyone in Cohort 11.

## How the Exercise Works

1. **Fork the Repository**: Participants should fork this repository to their GitHub accounts. They will have their own copy of the exercise repository to work on.

2. **Clone the Repository**: Each participant should clone their forked repository to their local machine using the following command (replace `<username>` with your GitHub username).   Alternatively, you can use the "Clone or download" button on GitHub and then click the "Download ZIP" option to download the repository as a ZIP file. Extract the contents to your local machine:

```
git clone https://github.com/<username>/Xander-Git-GitHub-Workshop.git
```

3. **Add Your Name**: Open the `names_exercise.py` Python script and add your name to the `names` list, where it says "Add participant names below this comment." Make sure to save the changes.

4. **Commit and Push**: After adding your name, commit the changes and push them to your forked repository.

```
git add names_exercise.py
git commit -m "Added [Your Name] to the names list"
git push origin main
```
   
5. **Merge**: After all the changes are made and reviewed, the organizer will merge the pull requests into the original repository (`Xander-Git-GitHub-Workshop`).

6. **Create Conflicts**: As part of the collaboration process, participants should deliberately make conflicting changes to the `names` list. For example, each participant should change the same line in the `names` list. This step will demonstrate how to resolve conflicts during collaboration.
   
## Running the Script

To see the current list of names, run the `names_exercise.py` script:

```python names_exercise.py```

The script will display different messages based on the number of names in the list: "No names added" if the list is empty, "Hello, my name is ..." if there's only one name, and "List of names for everyone in cohort 11" if there are multiple names in the list.

Happy coding!
