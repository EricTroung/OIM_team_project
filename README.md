# OIM_team_project
team project
Team Members: 
Eric
Olivia

3D Shape Generator
Description
This Python script allows users to create 3D shapes like cubes, spheres, cylinders, and more. It leverages libraries such as numpy, trimesh, and matplotlib for calculations and visualizations. Additionally, it includes features for boolean operations on these shapes and can interface with PrusaSlicer for model slicing.

Features
Generate 3D models (cube, sphere, cylinder, etc.)
Visualize 3D models using matplotlib
Perform boolean operations (union, difference, intersection)
Interface with PrusaSlicer for automatic slicing
Installation
Prerequisites
Python 3.x
PrusaSlicer (for slicing functionality)

Required Python Packages: Install the required Python packages using pip:

pip install numpy trimesh matplotlib

Commands
To create a cube: create cube with side [length]
To create a sphere: create sphere with radius [radius]
To create a cylinder: create cylinder with height [height] radius [radius]
... [other commands] ...
Slicing with PrusaSlicer
After generating a model, you can choose to slice it and open it in PrusaSlicer (ensure PrusaSlicer's path is correctly set in the script).