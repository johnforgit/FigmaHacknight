# FigmaHacknight
Saturday hacknight using figma API

## PDF IMPORTER  
This plugin is made with the intention of giving designers the freedom to import PDFs to their design space as an image and then work with it from there. Often times a designer has to go to a converting website and get the PDF converted to a format suitable to him and then import it to his Figma account. This plugin aims to avoid that by a single click of choosing the PDF.  

## Team Members
[John Philip George](https://github.com/johnforgit)  
[Manukrishnan P](https://github.com/manukris-mk8)  
[Sreevardhan P](https://github.com/SreevardhanP)  

## The working  
A basic UI is setup to select a PDF file which the designer wants to use. It is selected from the system. Using a python script it is sent to a server which extracts the images out of the PDF and sends it back to the designer. Instead of the image we collect the object and put it inside an HTML script. By this way one can see the image being loaded to Figma after the user selects the PDF.  
Also ensure you have a Figma account setup and from there you can create a new plugin and work on the code aspect of the design

## Libraries used  
The various libraries that are used are from the Python side of programming. You need to install Pillow, Flask and fitz. After installing the libraries, following the code should give you an understanding of how the python code works. The python code is written inside main.py  

## Configuring  
Configuring is a simple task. Ensure you have a Figma account and the latest python version. The code was written and compiled in VS Code but any other text editor of your choice will also do. You can also watch videos of setting up a plugin in Youtube from Figma.  

## Running  
Running in the code editor you use. We used VS Code to run our code. 
