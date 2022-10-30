# GIT

## Version Control

Version control can also be termed source control, is the practice of programmers tracking and managing changes to software code. Version control systems are software tools that help manage changes to source code over time. Version control systems help software teams work faster and smarter. An example is revert a file or project to a previous version, tracking modifications and who was responsible for modifying files, and compare changes between files.

### Version Control Types

- Local Version Control System (VCS): a local VCS has one database on a user's hard druve that stores changes to files.
- Centralized Version Control: need for collaboration within a team on a single file or set of files led a system with a single server storing all changes and file versions, which can be accessed by various clients.
- Distributed Version Control: a Distributed Version Control systemsaddresses the major vulnerability of the CVS with the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. To prevent this type of loss, a DVCS allows clients to create mirrored repositories. Programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.

### What is Git?

- Git is a distributed VCS which manages changes in files with snapshots. Each time a change to a file or project is save #(this is called a commit)#, a snapshot of the file is taken and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
- Git is primarily all local dependent to the user's machine. There is no need to reach back to a server and if the user is disconnected or not online they can still work.
- Git can track every single change applied to any file or directory and can detect file corruption or loss of information in transit. Also Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.
- Git can be found in three type of states:

- *Committed*: data is securely stored in a local database
- *Modified*: a file or project has been changed but not committed to the database
- *Staged*: flagged a file’s changed version to be committed in the next snapshot
Here is a pictorial of the above states:
![Git stages](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

### References

- [Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

- [What is version control?](https://www.atlassian.com/git/tutorials/what-is-version-control)

### Return

[Home Page](/code-102/README.md)
