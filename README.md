Please visit the official web page of [GRUB 2](http://www.gnu.org/software/grub/grub.html), for more information.

Example of use:

    grub-lshook.cfg: dynamic menu creation for all disks
    grub-lshook-boot.cfg: search and filtering: bootmgr ( Windows 7-10 ); /boot/vmlinuz ( Ubuntu )

    ( sudo ) cp grub.cfg grub-lshook.cfg grub-lshook-boot.cfg /boot/grub/
    ( sudo ) cp boot.jpg /boot/grub/
    
