# DiskCleaner - Diskcleaner a utility Program for Linux

DiskCleaner is a Disk Utility Program made for Linux. It uses inbuilt commands like autoclean, autoremove. DiskCleaner allows users to perform cleaning of cache present in their disk, it also cleans partial packages, no longer required packages, orphaned packages, freeing up space by cleaning cached packages, cleaning old kernals, removing trash etc.


# Features

DiskCleaner Enables the following Commands & Checks all the Files :
1) **Checks All The Drive Space Used by Cached Files.**
2) **Cleans all the Log files.**
3) **Get rid of partial packages.**
4) **Removes no longer required packages , orphaned packages.**
5) **Clears the trash , Man & deletes all the .gz and rotated files.**
6) **Clean-up the old kernels.**

# Commands
1) `apt -get clean && apt-get autoclean`
2) `apt-get remove --purge -y software-properties-common`
3) `apt-get autoremove -y`
4) `sudo apt-get -y remove --purge`
5) ` apt-get clean`

## Usage

To run DiskCleaner, follow these steps:

1. **Ensure root privileges**:
   DiskCleaner requires administrative privileges to function correctly. Run the script as root using `sudo`.

   ```bash
   sudo ./diskclean.sh

