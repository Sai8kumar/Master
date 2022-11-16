# Master
> git rev-parse --resolve-git-dir /var/lib/jenkins/workspace/test/.git # timeout=10
Fetching changes from the remote Git repository
 > git config remote.origin.url https://github.com/Sai8kumar/Master.git # timeout=10
Fetching upstream changes from https://github.com/Sai8kumar/Master.git
 > git --version # timeout=10
 > git --version # 'git version 2.31.1'
using GIT_ASKPASS to set credentials 
 > git fetch --tags --force --progress -- https://github.com/Sai8kumar/Master.git +refs/heads/*:refs/remotes/origin/* # timeout=10
 > git rev-parse origin/dev^{commit} # timeout=10
 > git rev-parse dev^{commit} # timeout=10
ERROR: Couldn't find any revision to build. Verify the repository and branch configuration for this job.
Finished: FAILURE
