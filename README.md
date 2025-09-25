Impress-Progress-Bar
====================

# UPDATE: 2025-09-25

- I created 2 versions of the macro: one that uses a line (rectangle) and another that uses an image.
- I modified the project to use a gradient instead of a rectangle position. I realized that the rectangles are arranged in front of  the header and footer, which is not ideal. I changed the gradient implementation to an image instead.
- To change the image, modify the `ProgressBarImage.xba` file and change the `ImageShape.GraphicURL` to point to your desired image. Also, modify the Height and Width if the image is not a square.
- Added a checkbox to allow skipping the first slide.

# ORIGINAL README

Macro to add automatically a progress bar to your Impress presentation. Tanks to Leo Barichello we have now a dialog box and some customization options.

How to install:

1.- Download the zip form github and extract its contents (there is a folder named ProgressBar that contains a BAS library files)

2.- Inside Impress go to the menu "Tools -> Macros -> Organize Macros -> Libreoffice Basic"

3.- Click in the "Organizer" button, and in the next dialog choose the "Libraries" tab. Look for the folder ProgressBar downloaded and click it so you see its contents. Accept and the library should be installed.

How to use: 

1st make a backup of your FINISHED presentation.

2nd execute the macro and a progress bar will be added to each slide, on top of whatever there is in it.

Use it freely but at you own risk, I wont be responsible for any loss or damage to your work or system.

Info on how to add/import a macro to your Open Office / Libre Office Suite is available on the net, so just use your favourite search engine to find how to do it.
