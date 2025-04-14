The Main.storyboardc file contained .nib files that may hide flags.
### Solution:
I used editnib to open the .nib files and searched for any hidden strings.

```bash

# Extract data from .nib files
editnib BYZ-38-t0r-view-8bC-Xf-vdC.nib

# Search for hidden flags
strings BYZ-38-t0r-view-8bC-Xf-vdC.nib | grep flag
```
### Flag Found:
flag-5932744F-4810-4A6C-BD8F-66FF3E115ED6
