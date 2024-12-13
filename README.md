# Zypher Linux 

Zypher linux is a linux distribution based on Arch Linux using the SysPatch system to install the modified configuration files and packages. Zypher is arch linux with a few tweaks.

## Installation

Install a base Arch Linux system and download the `patch.tar` file from the releases page:

Then run the following commands:

```bash
tar -xf patch.tar && sh patch.sh && rm -f patch.sh patch.tar
```