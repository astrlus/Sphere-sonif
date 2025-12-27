# Sphere-sonif
A tool to convert astrophotographs into sound. Inspired by NASA's sonifications, this tool replicates the same effect, however, with a different approach using colour averaging and star recognition.

The folder, Product, (and the stars folder) contains the program "Sphere Sonif'. The version in the base directory is the original program and the "Stars" Folder contains the modified program for a single parameter. 
Info about how the program works is in the Presentation File (Base folder)
Programming language used: Python
IDE used: Jupyter Lab

Image splitter used: https://imagy.app/split-image/
Image colour component finder: https://matkl.github.io/average-color/

All the libraries used can be download using "pip3 install <library name>" command in the terminal. 

NOTE: "AUDIOLAZY" LIBRARY HAS AN OUTDATED FOLDER PLACEMENT. PYTHON 10+ DOES NOT RECOGNISE THE "collections" FOLDER. USE PYTHON 3.9 IN A VIRTUAL ENVIRONMENT WITH "VIRTUAL: PYTHON 3.9" KERNEL SELECTED IN JUPYTER LAB.
Commands for a virtual environment (Only to be executed in the terminal), Omit quotations:
"python3.9 -m venv myenv"
"source myenv/bin/activate"

Use "cd <folder>" to change Jupyter Lab directory -- all in a virtual environment.

Keep experimenting with the program! Variables and Parameters are flexible to change, feel free to make any modifications for a desired output.

*Use the following website to split the image in the desired parts:
. imagy.app/split-image/
Use the following website to find out the average colour of a slice (of image) along with their R,G and B propotion.
. https://matkl.github.io/average-color/

*Coming back to this years later, it's a PRETTY CRUDE CODE--nevertheless, it did achieve what I was trying to achieve at the time.
