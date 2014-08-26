ips.py v0.1 
===========
A Python 3 module and a CLI program to apply and create IPS patches.

__Usage__

As a CLI program :
```bash
   ips apply path/to/original/file path/to/patch path/to/new/file
   ips create path/to/original/file path/to/modified path/to/new/patch
   ips help

   patch files can be .ips or .gzip
```

As a Python module :
```bash
   import ips

   ips.applyPatch(original, patch, newFile)
   ips.createPatch(original, modified, newPatch)
```

__What's an IPS patch ?__

A popular format for retro game ROM hacks
* http://zerosoft.zophar.net/ips.php
* http://www.romhacking.net/translations/

__Tests__

To run the tests :
```bash
   ips test
```
