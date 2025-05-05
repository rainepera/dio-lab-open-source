## Justification for non-contribution
Error when trying to push a branch with many files

While trying to contribute to the DIO community repository, I encountered an error when running the command git push origin feat/community/rainepera. 
The push failed due to the project being too large, which already contains files and changes from too many participants. Git returned errors such as:

RPC failed; curl 55 Send failure: Connection was reset

error: RPC failed; HTTP 500 curl 22

fatal: the remote end hung up unexpectedly

These errors are usually related to the push being too large (in this case, more than 3GB of data) and GitHub's limitations when transferring large amounts of data at once.

Even though my contribution was small, Git ended up trying to package and push the entire project again, which resulted in failure. 
So I decided to move on to the next stage of the bootcamp and leave this part of the contribution aside for now.
