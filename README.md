# Git Workflow Task

mr **nags**

We are learning how to use **Git**.

## Learning Outcomes

This includes:

* Creating a GitHub Repository.
* Giving permissions to users of GitHub.
* Cloning the repository.
* Creating Pull Requests.
* Merging the Pull Requests.
* Rejecting Pull Requests.
* Resolving Conflicts in Merges.

## Contribution Guidelines

Please kindly follow the below steps to contribute.

1. Go to `master` branch and pull the latest code.
2. Create a new branch from latest `master` branch.
3. Make changes to the content of the repository.
4. Add the changed files to the staging area.
5. Write a decent, understandable and sensible commit message.
6. Push the new branch with the changes.
7. Create a Pull Request from GitHub.
8. Write a nice message to convey what you have changed.
9. Request review from other reviewers and assign them too.
10. Get the Pull Request merged to `master` branch.

Make sure you delete the PR branch once the merge is completed.

Happy Open Sourcing! 🤘🏻

Following the above steps learned the below

* Cloning the repository.
* Creating Pull Requests.
* Merging the Pull Requests.





**Abhishek's Changes and contributions **

These are the following commands from the start that we have learned so far: -

What is Git and VCS?

  VCS means Version control system, a category of software tools that helps record changes to files by keeping a track of modifications done to the code.

**Use of Version Control System:**

- **A     repository:** It can be thought as a database of changes. It     contains all the edits and historical versions (snapshots) of the project.
- **Copy     of Work (sometimes called as checkout):** It is the personal copy     of all the files in a project. You can edit to this copy, without     affecting the work of others and you can finally commit your changes to a     repository when you are done making your changes.

**Types of Version Control Systems:**

- Local     Version Control Systems
- Centralized     Version Control Systems
- Distributed     Version Control Systems

**Local Version Control Systems:** It is one of the simplest forms and has a database that kept all the changes to files under revision control. RCS is one of the most common VCS tools. It keeps patch sets (differences between files) in a special format on disk. By adding up all the patches it can then re-create what any file looked like at any point in time.

 


 

**Centralized Version Control Systems:** Centralized version control systems contain just one repository and each user gets their own working copy. You need to commit to reflecting your changes in the repository. It is possible for others to see your changes by updating.

Two things are required to make your changes visible to others which are:

- You     commit
- They     update

![cvcs](file:///C:/Users/abhis/AppData/Local/Temp/msohtmlclip1/02/clip_image002.png)

The **benefit** of CVCS (Centralized Version Control Systems) makes collaboration amongst developers along with providing an insight to a certain extent on what everyone else is doing on the project. It allows administrators to fine-grained control over who can do what.

It has some **downsides** as well which led to the development of DVS. The most obvious is the single point of failure that the centralized repository represents if it goes down during that period collaboration and saving versioned changes is not possible. What if the hard disk of the central database becomes corrupted, and proper backups haven’t been kept? You lose absolutely everything.

**Distributed Version Control Systems:** Distributed version control systems contain multiple repositories. Each user has their own repository and working copy. Just committing your changes will not give others access to your changes. This is because commit will reflect those changes in your local repository and you need to push them in order to make them visible on the central repository. Similarly, when you update, you do not get other’s changes unless you have first pulled those changes into your repository.

 

Installation guides:

1) Make a GitHub account using email address.

2) install git bash.

3) command to configure git bash:

   A    git config –edit –global 

B  press I for inserting purpose

C   :wq for save and exit

D   :q for exit without saving 

E  git user.name returns user name

G git user. Email return user email

Basics command of git:

cd .. exit from current directory

pwd  shows current directory

cd x/git-tut for entering another directory 

Start . for windows to open current file a

Git clone for cloning the file use http link 

Open readme file and make some changes 

Git s for current status 

Git add file_name to add the file to github 

Git commit to make some commit 

Or use git commit -m “ dhhhfghfghjgh” 

Git checkout -b branch name for creating a new branch

Git branch shows all branch 

Git push –set-upstream origin branch name to be set as upstream 

Create the pull request with comments to the reviewer 

Reviewer needs to review and merge it or request changes.

Merge the changes into master branch.

Delete the branch in the GitHub.

 

 

 

 

 

 

 

How can I set github in vs code:

Open new terminal click on the powershell choose default shell and search git bash and clicked .