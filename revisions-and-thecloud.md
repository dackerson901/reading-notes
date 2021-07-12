# Version Control

- Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

# Local Version Control

- A Local VCS entails one database on your hard disk that stores changes to files.

# Centralized Version Control

- This system entails a single server storing all changes and file versions, which can be accessed by various clients.

# Distributed Version Control

- A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVS

- DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

# So, what is Git?

## Snapshots 

- Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

## Local Operations

- Git mostly relies on local operations because most necessary information can be found in local resources.

## Tracking Changes

- Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit. 

## Loss of data

- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

## States

- Files in Git can reside in three main states: committed, modified and staged.

## Graphical Clients

- Git includes inherent Graphical User Interface (GUI) tools.

# Remote Repositories

## Cloned Repositories 

- As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.

## Seeing Your Remotes

- By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.

- By using git remote -v, you can view all the remote URLs next to their corresponding short names.