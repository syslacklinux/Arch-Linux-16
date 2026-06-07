<img width="920" height="300" alt="Arch Linux 16 Logo" src="https://github.com/user-attachments/assets/ab1d51fd-8cad-47bc-9738-22f7ca945999" />

# Arch-Linux-16
A lightweight and flexible Linux® distribution that tries to Keep It Simple. Currently we have official packages optimized for the 8086 With ELKS
the community maintained continuation of 16-bit support for Arch Linux

Installation

Build ELKS images On a modern Linux machine git clone https://github.com/jbruchon/elks.git cd elks make

Write floppy image

Insert a real floppy disk.

Use dd to write the image:

sudo dd if=elks.img of=/dev/fd0 bs=512

Boot hardware from floppy

Insert the floppy into your vintage PC.

Power on; ELKS should boot into its shell.

Login as root (no password).

Install to HDD

Partition the HDD using DOS tools or ELKS utilities.

Format with FAT or MINIX (mkfs.minix).

Copy ELKS system files from floppy to HDD.

Adjust boot sector or use a bootloader (ELKS includes simple boot code).

Reboot with HDD as primary boot device.

Login as root then vi /etc/issue then i Then Change ELKS 0.7.0 To Arch Linux 0.7.0-arch1-1 then esc then :wq
