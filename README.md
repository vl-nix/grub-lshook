Please visit the official web page of [GRUB 2](http://www.gnu.org/software/grub/grub.html), for more information.

Example of use:

    grub-lshook.cfg: dynamic menu creation for all disks
    grub-lshook-boot.cfg: search and filter for each disk partition - 
        bootmgr ( Windows 7-10 ) & /boot/vmlinuz ( Ubuntu )

    ( sudo ) cp grub.cfg /boot/grub/ ( optional )
    ( sudo ) cp boot.jpg /boot/grub/ ( optional )
    ( sudo ) cp grub-lshook.cfg grub-lshook-boot.cfg /boot/grub/
    
