# Dimensional

### Overview
- This project contains the base SCSS files that override the Boostrap defaults. You can compile the SCSS files to create an output CSS file. The SCSS files are found in '/dimensional-theme'.
- This project includes a style and components page as well as a few template pages.
- This folder includes a light and a dark theme.

### Overview of '/dimensional-theme'
- Each theme has it's own base SCSS file.
- Each theme imports theme-specific variable overrides and shared component overrides. It also includes the '/bootstrap' folder, which are the the untouched Bootstrap files.
- Each theme also includes styles for the multiselect component. You can remove this reference if you decide to use another plugin.

### How to build the CSS file
1. Navigate to the root folder and run `npm install` to install the node-sass package then run `npm run scss`. This command will watch any changes made in '/dimensional-theme' and compile the CSS files.
2. The output files are in '/design-system/assets/css'

### "Sentinel" font family
- The Headings use "Sentinel". If the font files aren't included, the family defaults to Georgia or whichever serif font is default on the viewer's computer.
