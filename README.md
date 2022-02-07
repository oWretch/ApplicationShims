Application Shims
=================

These shims are created with Microsoft's Application Compatibility Administrator which can be downloaded as part of the [Assessment and Deployment Toolkit][adk]. These shims allow older applications to run on newer Windows versions by tricking the application into thinking it is running on something other than what it is.

To use these shims, they must be installed on your computer. Launch an elevated command prompt, then install the relevant shim by running `sdbinst.exe shim.sdb`. Shims can be uninstalled by running `sdbinst.exe -u shim.sdb`. Once installed, you can remove the `.sdb` file from your computer.

[adk]: https://docs.microsoft.com/en-au/windows-hardware/get-started/adk-install

List of shims
------------

* `Age of Empires 3.sdb` Allows a user to run Age of Empires 3, plus both expansion packs without administrative rights. Tested working with the Steam version of the game.
