## All About the BIOS

The BIOS stands for basic input/output system. It is located on its own ROM or (now) flash memory chip and is  firmware. It has a number of different roles, and most importantly, it provides instructions to the CPU to load the operating system. The BIOS is also used to initialize the computer's hardware as the computer is being booted.

### The CMOS Chip

One of the jobs of the BIOS is to check its custom settings stored on a *complementary metal oxide semiconductor* chip. This chip contains Hardware settings, Boot sequence, and the Date and Time. It is volatile so it requires a CMOS battery. On more contemporary systems this has been replaced with flash memory.

### The BIOS Process

The first step of the BIOS is to run a POST, Power-On Self Test. This checks to ensure your hardware configuration is valid and working properly. The BIOS will then check its custom settings located on the CMOS chip. Then the BIOS looks for a Master Boot Record, or MBR, stored on the boot device and uses it to launch the bootstrap loader which will start the OS. See [here](http://www.dewassoc.com/kbase/hard_drives/master_boot_record.htm) for more detail.

### UEFI

UEFI replaced the traditional BIOS on PC's in 2007. BIOS was outdated in that it only supported 2.1 TB drives or less and only ran in 16-bit processor mode, and only has 1 MB of space to execute in. UEFI has a faster boot process, running in 32-bit or 64-bit modes, has a theoretical limit of 9.4 zettabytes, and supports Secure Boot, which means the operating system can be checked for validity to ensure no malware has tampered with the boot process. There is also a new graphical user interface and you can use your mouse.



