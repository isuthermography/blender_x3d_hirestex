This blender plugin (compatible with 2.93) provides an alternative
input/output plugin for Blender that gives more precision in .x3d
texture coordinates. It is essentially a copy of the blender .x3d
output plugin with some trivial changes

This directory (or a symbolic link to it)
can go in your ~/.config/blender/<version>/scripts/addons

Then you need to run blender, go to Preferences...Addons
and enable the new "Web3D X3D/VRML2 format (highres texture export)"
entry. Don't forget to save your changes to the preferences!

Once you have done this, the new option should show up in
the import/export menus
