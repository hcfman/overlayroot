# overlayroot
Clone of elegant overlayRoot.sh solution from Pascal Suter for running a raspberry pi from a read-only rootfs mount.

It has been amended to keep working on recent raspberry pi's as things change.

This is a beautiful little script that facilitates running a raspberrypi with a read-only mounted filesystem whereby logfiles and other minor writes would then be written to memory only. The result of this is a stable running system that should be pretty much immune from SD card corruption. Read more on Pascal's site for details.

The original can be found here:

http://wiki.psuter.ch/doku.php?id=solve_raspbian_sd_card_corruption_issues_with_read-only_mounted_root_partition

This repo was created in order to aid with the use of this solution in automatic install scripts. The master branch will be kept working for the latest version of raspberrypi. Other branches will be created to support other configurations.
