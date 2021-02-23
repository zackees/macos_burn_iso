# macos_burn_iso

From https://osxdaily.com/2015/06/05/copy-iso-to-usb-drive-mac-os-x-command/

  * Insert USB disk
  * use `diskutil list` to find out the disk name (should be like `/dev/disk3`)
  * run `sudo dd if=<PATH TO ISO FILE> of=<PATH FROM DISK UTIL>`
