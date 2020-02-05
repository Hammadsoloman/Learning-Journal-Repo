# Remote Repositories


## What is a remote in Git?
* A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server.
In contrast to a local repository, a remote typically does not provide a file tree of the project's current state. Instead, it only consists of the .git versioning data

## Steps to work with Git
1. clone from Github
2. check the status using `git status`
3. add using `git add`
4. commit using `git commit`
5. push using `git push`

### what we could do by using git remote ?
*view all the remote URLs next to their corresponding short names.*

## What is Version controlr

its standerde to **VC** that's allow you to visit several versions in your project and save changes which will make your mistake fixed easly.

![Version controlr](https://media.geeksforgeeks.org/wp-content/uploads/20190624140224/cvcss.png)

## what command in git ?

1. `git clone [url of the file]`: this command will install the repo.
2. `git status`: this command will check from what you changed.
3. `git add [file name]`: this command will add the changes.
4. `git commit -m '[some massege to remmber the changes]'`: this command will save the changes with the commit that you write.
5. `git push origin master`: this command will save your changes on the cloud.
 ![command](https://marklodato.github.io/visual-git-guide/basic-usage-2.svg)
 
## Snapshots:
- When you make a change to your file.. gIt creates an identical snapshot version called commit.. Git only store it as a reference to the original version.
![snapshots](https://www.exoscale.com/static/syslog/2016-01-20-feature-announcement-snapshot/snapshots-cover.png)

### Git detects errors, corruption, loss in your files.

#### `States`
- _**Commited**_ keeps the data securely stored in the local database.
- _**Modified**_ changes have been applied but not commited to the database.
- _**Staged**_ Flagged the file and changed the version to be committed in the next snapshot.
![states](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

##### You can find more information and tutorials through [Git guid](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png).

Edited by Anas Zain on Feb 3 at 3:35pm
![image](https://www.git-tower.com/learn/media/pages/git/ebook/en/command-line/remote-repositories/introduction/-1045933932-1580720127/basic-remote-workflow.png)


For more information visit this [site](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)
