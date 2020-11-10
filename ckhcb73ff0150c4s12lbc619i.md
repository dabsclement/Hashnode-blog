## How to fix Started Hold until boot finishes up issues on Ubuntu Linux.

One of the most common issue I always run into using Ubuntu Linux is the started hold until boot finishes up issues.
This issue is always caused by some many things like Plymouth bug, mounting a device that no longer exists, memory fulling up amongst others. In my case the issue in that my memory is always filling up because I have a little memory allocated to run Linux from the hard drive partition.
In this article, I will be focusing on how to solve the **started hold until boot finishes up** issue as related to memory space.

The best way to solve this issue is to avoid it from happening in the first before you run into the problem you would have been receiving warnings that your memory is filling up and you need to free them up. at the time of receiving the warning, the best thing to do is to delete unused or unwanted files from your drive, doing this will help you avoid running into the boot issue. if eventually you didn't free up your memory space and shut down your system the next time you put on your system you will encounter the **started hold until boot finishes up** issue.

The following steps are how to solve the issue

1. When booting press ESC key to enter in the Grub menu.
2. Select the advanced boot in Grub menu.
3. Select and enter recovery mode.
4. Select **root** in the recovery menu.
5. Open the terminal and list all the directories on your drive
6. From your terminal delete unwanted files and folders from drive.
7. Reboot your system.
with the above steps, you should be able to solve started hold until boot finishes up issue related to memory space on ubuntu Linux.


