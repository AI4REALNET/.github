<div align="center">

# Contribution Guidelines
</div>

### AI4REALNET - AI for REAL-world NETwork operation

Welcome to AI4REALNET's open-source community! We appreciate your interest in contributing to our projects. Your contributions are crucial for fostering innovation and driving positive change.

These guidelines are designed to assist you throughout the contribution process. Whether you're fixing a bug, adding a feature, or suggesting improvements, your input is highly valued.

Please take a moment to review the outlined steps below. Should you have any questions or require assistance, do not hesitate to contact our community or project maintainers. 

## Step-By-Step

1. **Fork the Repository:**

Visit the repository.
Click on the "Fork" button in the top-right corner. This will create a copy of the repository under your GitHub account.

2. **Clone Your Fork:**

Go to your forked repository.
Click on the "Code" button and copy the URL.
Open your terminal and run

    git clone <repository-url>

to clone the repository to your local machine.

After clonining install the necessary dependencies, and setup the development environment.

3. **Create a Branch:**

Navigate into the cloned repository using:

    cd <repository-name>

Once you are in the repository's directory, create a branch to work on, based on the main development branch (eg. **develop** or **main**).

When creating a branch make sure it is named appropriately.  If you're adding a new feature, prefix your branch name with **'feature/'** followed by a descriptive name. If you're addressing a bug or making a fix, start your branch name with **‘bug/’** or **'fix/'**, respectively. 

To do so, run:

    git branch <branch-name>

    git checkout <branch-name>

or 

    git checkout -b <branch-name>


4. **Make Changes:**

Make the necessary changes to the codebase using your preferred editor or IDE.
Run Tests (if applicable):

If the project has tests, ensure they pass locally by running npm test, pytest, or the appropriate command for the project's testing framework.

5. **Commit Changes:**

Add your changes to the staging area using 

    git add <file-name>

or add all files 

    git add . 

Commit your changes with a descriptive commit message using
 
    git commit -m "Your message here"

6. **Push Changes:**

Push your changes to your forked repository on GitHub using 

    git push origin <branch-name>

7. **Create a Pull Request (PR):**

Go to your forked repository on GitHub.
Click on the "Compare & pull request" button next to the branch you just pushed.
Fill out the pull request template with details about the changes you've made.

8. **Review and Address Feedback:**

Wait for project maintainers to review your pull request.
Address any feedback or changes requested by the maintainers by making additional commits to your branch.

9. **Merge Pull Request:**

Once your pull request is approved, a project maintainer will merge your changes into the main branch.

10. **Sync Your Fork (Optional):**

To keep your fork up-to-date with the original repository, you can periodically sync it by adding the original repository as a remote and pulling changes from it.
