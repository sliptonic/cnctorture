# Contributing to this Catalog

So you want to contribute?  Awesome!

Each file lives in it's own directory and should have at least the following:

- A FreeCAD project file (fcstd).

    This is necessary so the file can be revised and maintained over time.
    The document should have one top-level document object.
    The top-level object should have its label set to match the file name (eg Drilling1)
    The file should be saved with a thumbnail included (Preferences/Document 'Save thumbnail into project when saving document')
- A STEP file.  This allows the shapes to be used by other CAD/CAM applications. From FreeCAD, Select the top level object and export as a step with colors (eg Drilling1.stp)
- Screenshot image
   Create a screenshot image of the part to be used on the website.  The image should be 320x320 with transparent background.  [This Macro](screenshot.FCMacro) can be useful

    For 2D files, export a DXF and/or SVG file
    DXF and SVG file for 2D
- Create a README file explaining the purpose of the file, key features, and any other notes. It's worth copying the README.md file from one of the other examples as a starting point.  They contain some additional boilerplate to help with navigation on the site.


[Home](https://sliptonic.github.io/cnctorture/)
