Please visit the official web page of [GRUB 2](http://www.gnu.org/software/grub/grub.html), for more information.

Example of use ( grub.cfg ):

    # Dynamic menu creation for all disks

    ls
    for hdd in $lshook; do
      menuentry "Disk lshook: $hdd" --source="
        set root=$hdd
        chainloader +1"
    done
