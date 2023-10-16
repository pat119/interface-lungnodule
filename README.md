# Summary
A custom Slicer module for drawing contours on lung images and annotating them. Designed for radiologist annotation.

## Code
- Currently not public

## Features
- Uses LIDC dataset annotations (https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=44499647)
- Loads DICOM images into Slicer for in-depth examination
- User can contour and annotate observed lung nodules, as well as add additional comments
- Allows for the creation of 'presets' for faster annotation
- Saves contour and annotation data in a format that can be parsed into pylidc objects
