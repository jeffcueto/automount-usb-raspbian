# automount-usb-raspbian
automount rasbian jessie lite
in this tutorial we are going to use a  udev script for automount  USB :
we need to create a file  11-media-by-label-auto-mount.rules in /etc/udev/rules.d/
after we've created script and saved it, reload udev with:
udevadm control --reload-rules

 udev  should automatically create a driectory under /media.
