# Explanation for Question 5

1. Device inspection
   - I listed block devices with lsblk to identify the available disks and partitions.

2. Mounted filesystems
   - I reviewed the mounted filesystems with mount so the storage layout could be documented.

3. Disk usage
   - I checked df -h to observe used and available disk space across the important filesystems.

4. Inode usage
   - I checked df -i to evaluate inode consumption and confirm whether the system was running out of file entries.

5. Storage conclusion
   - The system currently has sufficient free space and inode capacity, but regular monitoring and cleanup are still recommended as the workload grows.
