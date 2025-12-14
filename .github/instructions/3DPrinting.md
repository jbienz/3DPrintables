---
applyTo: '**'
---

These are instructions for working with 3D printing files hosted in a GitHub
repository.

# File and Folder Conventions

- File and folder names are generally CamelCase with no spaces.
- The folder structure for the repo is Manufacturer/Product/Print. For example:
  Tesla/Model3/Cupholders.
- Each print contains the following subfolders:
  - Design - If available, the Fusion 360 or similar export of the design
    (*.f3d) and the exported custom parameters (Parameters.csv).
  - Media - Images of the design and actual print of the part.
  - Print - At bare minimum the .stl file. Usually also a .3mf file that is
    ready to print with recommended settings such as supports and infill.
- Each print folder should also contain a README.MD which provides an overview
  of that specific print.
- In the root of the repo is another README.MD. This root READ.ME links to all
  of the print project READ.ME files, shows one image from the project scaled
  down, and a short excerpt of the print project README description.

# Generating a new Print Project README.MD

Whenever generating hyperlinks, the text of the link should just display the
filename and not the full path.

Below are the steps for generating a new Print Project:

1. Review [Tesla/Model3/CupHolders/README.MD](Tesla/Model3/CupHolders/README.MD)
   as an example of a good README.MD.
2. The README.MD must include the CC BY-NC-SA 4.0 license.
3. The Background section should describe the project. Please generate some
   placeholder text based on the context you have available and I will fill it
   in.
4. The Background section should also include one image from the Media folder.
   If the Media folder includes Design.jpg or Design.png, use that.
5. In the Design section, create a hyperlink to the .f3d file by name if it
   exists and explain that the model is parametric. If no .f3d file exists,
   mention it as a warning and generate placeholder text for me to fill in.
6. If the Design folder includes a Parameters.csv file, be sure to create a
   Parameters table in the Design section. This table should show Name,
   Expression and Comments from the CSV and should have a header row.
7. In the Printing section, if there is an image under Media whose filename
   starts with "Print", include that image in this section.
8. In the Printing section, create a hyperlink to the .stl and also create a
   hyperlink to the .3mf if it exist. If the .3mf exists, explain that it
   includes the recommended print settings such as supports and infill.
9. If additional images exist that have not been embedded yet, create an Images
   section and embed (not link) to those images here.
10. Do not create a miscellaneous "Files" section. All files should already be
    embedded, linked or used in other sections. If there are additional files
    that have not been referenced elsewhere in the document, please warn me.
11. Follow the steps below to Update the root README.MD to include the new Print
    Project.

# Updating the root README.MD to include the new Print Project

Here are the steps for updating the root README.MD after creating a new Print
Project README.MD:

1. Add a new entry under the Models section for the new print project. This
   section should be sorted alphabetically by Manufacturer, then alphabetically
   by print project. If the manufacturer already exists, use it. If it doesn't
   exist, add it where it belongs alphabetically.
2. Link to the print project using the print project name from its own
   README.MD.
3. Include one image from the print project Media folder. If the Media folder
   includes Design.jpg or Design.png, use that. Be sure to use the img tag with
   a specified width of 400 to ensure it fits with the other images.
4. Include a short excerpt from the print project README.MD Background section.
