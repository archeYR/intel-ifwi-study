# intel-ifwi-study
Files required for mkboot:
* cmdline - cmdline for Linux kernel or Multiboot image
* bootstub - <a href="https://github.com/archeYR/sfi-bootstub">SFI-Bootstub</a>  binary.
* font - 8x16 binary font (<a href="https://github.com/viler-int10h/vga-text-mode-fonts/blob/master/FONTS/PC-IBM/VGA8.F16">that one</a>  was tested), required for framebuffer logging to work in SFI-Bootstub.
* kernel - Linux kernel image or Multiboot 1 specification compliant image.
* ramdisk - Initial ramdisk image.
