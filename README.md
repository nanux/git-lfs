# Git LFS Demo Repository

Git LFS implementation is behaving differently for images that are under 10MB.

## Git LFS is tracking

* *.tif files
* *.log files

## Interesting branches

* *rover-with-stars* - rovew_with_history.jpg is under 10MB and has image difference in second revision (can you spot it?)
* *borneo-history* - has changed borneo_in_fire_history.tif changes
* *rover-jpg-history* - rover_with_history.jpgs went from (normal file => image LFS file < 10MB => image LFS file > 10MB)
* *update-galaxy* - updated galaxy.jpg file
