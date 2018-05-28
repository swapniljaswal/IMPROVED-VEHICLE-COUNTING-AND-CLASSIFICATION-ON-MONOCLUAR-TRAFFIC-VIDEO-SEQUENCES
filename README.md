# IMPROVED VEHICLE COUNTING AND CLASSIFICATION ON MONOCLUAR TRAFFIC VIDEO SEQUENCES
This project is a computer vision based vehicle counting system. The system is capable of performing vehicle detetcion, tracking, counting, classification (into light medium and heavy), speed estimation and traffic flow estimation. It harnesses the power of computer vision to get deeper insights into our traffic. The focus is on development of vehicle counting techniques and their comparative analysis on datasets.

## Getting Started
Download a copy of the project onto the system using a web browser or terminal commands. Unzip the porject and you are good to go.

### Prerequisites
Python v3.5+
OpenCV - Open Source Computer Vision v3.4+ 
Anaconda (Create a separate environment for your project)

Use the following commands to install the packages into your environment:
conda env create -f environment.yaml
source activate cv

Or you can install everything globally. Search for step by step guides to install OpenCV. The dependencies will be installed on the way.

## Files on the box
Why do I see so many files and what are their roles?
Here's an overview of the files.

single_ref_line.py : Vehicle Counting using Single Reference Line
multiple_reference_lines.py : Vehicle Counting using Multiple Refernce Lines
region_based.py : Region based Vehicle Counting System, includes a bonus speed estimation module as well!
run.py : The final system. Multiple reference lines based counting coupled with speed estimation and traffic flow estimation.

All the files have the module for vehicle classfification and video writing.

## Let's run this thing

Activate your environment. Change the directory to the project Folder. Run the file using python
Example:
python run.py
python single_ref_line.py
