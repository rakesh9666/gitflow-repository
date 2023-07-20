# gitflow-repository
git flow branching strategy

Steps to complete my assignment 

# 1 Create a new directory for your project
mkdir my_project
cd my_project

# 2 Initialize a new Git repository
git init

# 3 Initialize Git Flow
git flow init

# 4 Create Remote Repository in your github account 
ex: git-flow repository

# 5 Connect with remote repositoty
remote add origin <url>

Create Develop Branch (Local & Remote):

# 6 Create and switch to the 'develop' branch (locally)
git checkout -b develop

# 7 Push the 'develop' branch to the remote repository
git push -u origin develop

Create Feature Branches (Local & Remote):

# 8 Create and switch to 'feature-1' branch (locally)
git checkout -b feature-1

# 9 Push the 'feature-1' branch to the remote repository
git push -u origin feature-1

# 10 Create and switch to 'feature-2' branch (locally)
git checkout -b feature-2

# Push the 'feature-2' branch to the remote repository
git push -u origin feature-2

Work on your feature branches
Make changes in your code on each feature branch and commit your work

11 git add .

12 git commit -m "Implement feature-1"

13 git push -u origin feature-1 
into dev by creating a pull request 

15 Define Branch Policies:
To ensure a smooth collaboration process and code review, define branch policies for the remote repository. For example, require pull requests (PRs) and code reviews before merging into develop or master branches.

16 Create Pull Requests and Merge:
Create pull requests for each feature branch to merge them into the develop branch.

18 On the remote repository, navigate to the pull request section and create a new pull request for feature-1 and feature-2 into develop. Assign reviewers and wait for their approval.

19 Once approved, you can merge the pull requests into the develop branch, and the changes will be reflected in your local develop branch as well.



repository link : https://github.com/rakesh9666/gitflow-repository.git


 
