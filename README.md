# Single GPU Start and End scripts (personal)

## My system details

GPU: RTX 2060 (TU106) and Proprietary Nvidia drivers installed. Nouveau drivers as fallback drivers.
Host OS: Fedora 40 with Gnome

## Script directories

Follow this [guide](https://github.com/QaidVoid/Complete-Single-GPU-Passthrough) for more details as to how to use these.

### Start script

```/etc/libvirt/hooks/qemu.d/win11-singlegpu/prepare/begin/start.sh```

### End script

```/etc/libvirt/hooks/qemu.d/win11-singlegpu/release/end/revert.sh```
