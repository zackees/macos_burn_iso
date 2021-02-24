# macos_burn_iso

From https://osxdaily.com/2015/06/05/copy-iso-to-usb-drive-mac-os-x-command/

  * Insert USB disk
  * use `diskutil list` to find out the disk name (should be like `/dev/disk3`)
  * run `sudo dd if=<PATH TO ISO FILE> of=<PATH FROM DISK UTIL> bs=1m` (I don't know what the `bs=1m` means).
    * Example: `sudo dd if=~/Desktop/Win10_20H2_v2_English_x64.iso of=/dev/disk4 bs=1m`
