# DevOps-Beginners-to-Advanced-with-Projects  


## Manual VM Setup  

In this section, we learned that the best way to get the hang of automation is to first manually walk through each step. To put this into practice, we set up two virtual machines—one with CentOS and the other with Ubuntu.

Along the way, I quickly realized that not all virtual machine setup tutorials are created equal. For example, earlier tutorials assumed I knew not to click the reboot button that automatically pops up in the VM after downloading your chosen flavor of Linux.

But Imran had us covered. He took the time to point out a much better way: instead of rebooting from the VM itself, he advised us to head back to the Oracle VirtualBox Manager, right-click on the VM, and shut it down from there. This simple tip saved me from getting stuck in a frustrating loop where the VM kept trying to reinstall Linux every time I powered it on.

From there, we went into the settings, clicked on Storage, and then selected the empty disk under Controller: IDE. After that, we right-clicked the disk icon next to the Optical Drive and removed the Linux installation disk from the virtual drive. This step ensured the VM wouldn’t try to reinstall the OS every time.

If I learn nothing else from this course, I’m grateful I learned this. It was a small step, but it saved me a lot of time and frustration!


## Automatic VM Setup 
