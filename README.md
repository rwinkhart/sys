# sys - rwinkhart patches
This repository holds my custom patches atop the Go sys module.

The only changes in the master branch are this README and the patches in the `1patches` directory. The patches are applied on other branches and tagged releases are available for import from the releases page.

# How To?
Copy the desired patch file(s) into a new branch (cloned from upstream master) and apply with `patch -p1 < patchfile.patch`.
