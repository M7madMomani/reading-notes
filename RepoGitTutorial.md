![I1](https://s3-ap-northeast-1.amazonaws.com/samurai-blog-media/blog/wp-content/uploads/2019/11/git-lg.png)

> # What is git ?

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project (called commit) Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
![I2](https://chronicle.brightspotcdn.com/dims4/default/803b33a/2147483647/strip/true/crop/792x416+0+92/resize/1200x630!/quality/90/?url=http%3A%2F%2Fchronicle-brightspot.s3.amazonaws.com%2Fa3%2F27%2Fd09b3017d21e39d901f54b81978c%2F55c6a744f320f9c830bdf9cbd9d10055.jpg)
> # why git ?


* Git mostly relies on local operations that are allowing one to continue work on a project even when not online or on a VPN.
* Git can Tracking Changes 
* Git makes it extremely difficult for a snapshot of your file that is committed to being lost..
* Files in Git can reside in three main states: committed, modified and staged. 
    1. Committed : Data is securely stored in a local database 
    1. Modified : File has been changed but not committed to the database
    1. Staged : Flagged a file’s changed version to be committed in the next snapshot
* Saving Changes : All files in a checked out (or working) copy of a project file are either in a tracked or untracked state.
    1. Tracked :Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
    1. Untracked : Untracked files were not in the last snapshot and do not currently reside in the staging area.


![I3](https://www.git-tower.com/learn/git/ebook/en/command-line/remote-repositories/introduction/basic-remote-workflow.png)

> # Remote Repositories
In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

# <span style="color:#ff0066"> HAVE A NICE DAY </span>.



