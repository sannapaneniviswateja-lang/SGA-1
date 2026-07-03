# Explanation for Question 3

1. Link creation
   - I created one regular file, one hard link, and one symbolic link to observe how Linux manages file aliases.

2. Inode comparison
   - I used ls -li and stat to inspect inode numbers. The hard link shared the same inode as the original file, while the symbolic link had a different inode.

3. Content access
   - I read the file through all three names and confirmed that they each accessed the same content while the original file existed.

4. Deleting the original
   - I removed the original file name and observed that the hard link still worked because it referenced the same inode.

5. Symbolic link behavior
   - The symbolic link stopped working because it depends on the target path, not the inode. Once the target name was removed, the link became broken.
