# sdboot-mkentry
This script will generate entries for systemd-boot (mostly) automatically.

# usage
`sdboot-mkentry [-h] [-o opts] [-s target] -k kernel -t title filename`

-h,--help               display this text
-o,--opts "opts"        additional string to append to 'options' line
-k,--kernel "kernel"    kernel to use (vmlinuz and initramfs must exist)
-t,--title "title"      entry title to display in boot menu

'filename' should not include a path.

'root' and, if needed, 'cryptdevice' and 'rootflags' will be confgiured
automatically, and any CPU microcode that's installed will be included. The
root partition will be set to be mounted in rw mode."
