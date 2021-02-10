# sandbox
chroot mount script


$ vim sandbox.sh
:set ff=unix
:wq
$ chmod 777 sandbox.sh

mount
./sandbox.sh -m rootfs
unmount
./sandbox.sh -u rootfs
