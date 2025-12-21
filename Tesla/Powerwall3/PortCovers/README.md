# Powerwall 3 Port Covers

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

**IMPORTANT:** Please be aware that these designs are licensed under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). In short,
you can print them and modify them freely for personal use. But if you want to
use them commercially or sell them for profit, you'll need to contact me for a
different license. Please give me credit when you can, and if you make
significant changes please share those too.

## Background

![](Media/Hero.jpg)

I'm very happy to have such a clean install of my Powerwalls. I have no conduit
running between the units or the ceiling. So it bothered me how unfinished the
knock-out ports looked one each side of the units.

## Design

![](Media/Design.jpg)

The Fusion 360 design file is [PortCovers.f3d](Design/PortCovers.f3d). It's
fully parametric in case you want to modify something.

Parameters

| Name             | Expression            | Comments                                                                                          |
| ---------------- | --------------------- | ------------------------------------------------------------------------------------------------- |
| Width            | 156 mm                | How wide the badge is.                                                                            |
| LeftHeight       | 163.5 mm              |                                                                                                   |
| RightHeight      | LeftHeight - 6 mm     |                                                                                                   |
| LeftLoftDepth    | 4 mm - FrontFaceDepth |                                                                                                   |
| RightLoftDepth   | 8 mm - FrontFaceDepth |                                                                                                   |
| LogoCutDepth     | 1.5 mm                | How deep the logo is cut into the badge.                                                          |
| LogoCutOffset    | 0.75 mm               | How thick the outline of the logo cut is.                                                         |
| FlareHeight      | 20 mm                 | How tall the rear notch is cut to make way for the bottom right flare in the powerwall port area. |
| FrontFaceDepth   | 0.5 mm                | How deep the face goes before the loft starts                                                     |
| FaceCornerRadius | 3 mm                  | How rounded the face corners are.                                                                 |

## Printing

Two ways to print:

1. [PortCovers.3mf](Print/PortCovers.3mf) - A Prusa Slicer project ready to
   print with recommended settings
2. [Left.stl](Print/Left.stl) and [Right.stl](Print/Right.stl) - Regular STL
   (see recommended settings below)

The included `.3mf` contains the recommended print settings such as supports,
layer height and infill. If you prefer to use the standalone STLs, use the
`.3mf` as a reference for settings.

I printed with a layer height of 0.20 mm and 15% infill. The prints pictured
were printed with
[SUNLU Silk Silver Filament](https://www.amazon.com/dp/B0B5ZLFTRN). If you use
silk filaments, print the first layer very slow to achieve the best possible
face.

## Images

![](Media/Install01.jpg)

![](Media/Install02.jpg)

![](Media/Install03.jpg)
