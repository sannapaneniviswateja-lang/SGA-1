# Explanation for Question 4

1. Open files inspection
   - I used lsof to view open files and descriptors in the current environment. This helped identify which files were in active use.

2. File descriptor demonstration
   - I opened app.log through file descriptor 3 and confirmed the mapping using /proc. This showed how Linux manages file access through descriptors.

3. Redirection examples
   - I redirected normal output to stdout.txt and errors to stderr.txt. I also combined both streams into one file, demonstrating how shell I/O redirection works.

4. Resource limits
   - I checked the ulimit values to understand the shell resource constraints that affect file and process handling.

5. I/O conclusion
   - Linux handles input and output through streams and file descriptors, and shell redirection allows those streams to be routed to files or devices.
