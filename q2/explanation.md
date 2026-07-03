# Explanation for Question 2

1. Workspace creation
   - I created the secure project directories for documentation, source, and logs. This gave the project a structured location for its files.

2. File creation
   - I created the required project files so the permission changes could be demonstrated on real files.

3. Permission review
   - I checked the initial permissions before applying the security settings. The directories initially had broad access.

4. Permission change
   - I restricted the directories to mode 750 and the project files to mode 640 where appropriate. This reduced access to authorized users only.

5. Umask review
   - I checked the effective umask value. The value was 0022, which influences the default permission bits for newly created files and directories.

6. Security conclusion
   - These permission settings protect project data by limiting read, write, and execute access to the owner and the required group members.
