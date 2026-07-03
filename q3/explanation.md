Explanation for Question 3
=========================
This section summarizes the link analysis experiment that was performed with a regular file, a hard link, and a symbolic link. The results show that hard links share the same inode and remain usable after the original file is deleted, while symbolic links point to a path and break when the target is removed. This highlights the difference between inode-based links and path-based links in Linux.
