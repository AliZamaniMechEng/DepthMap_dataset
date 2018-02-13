# Environment Radomization

This code uses **Blender**, an open source 3D graphics and animation software, to generate data for the training of a **nerual network** to recognize a UTSA Road Runner object in a scene. The premise is to use a technique called **Domain Randomization** train a neural net using synthetic data so that may perform in the real world without further alteration of the data or system. 

In the domain randomization directory there is a dr_script which uses functions from bpy_fun to generate randomized scenes.

Blender is downloadable at "https://www.blender.org/". 

Example positive testcase:

![alt tag](https://github.com/brothaman/DepthMap_dataset/blob/master/domainRandomization/data/positive/set3000_image0.png)

and negative testcase:

![alt tag](https://github.com/brothaman/DepthMap_dataset/blob/master/domainRandomization/data/negative/set0_image0.png)

Intallation:

-Download the latest blender build (script was tested on v2.72), install and open blender.

Either open with blender the .blend file in the "blender file" folder, or ,alternatively, do the following:

-Change the display button on the bottom left (represented by a cube symbol, left of the view menu) to text editor.

-Click new, then simply paste the contents of pby_script.

Usage:

-Change the saving path name "YourPath" at the end of the script to whatever directory you wish to save the output images and depth maps.

-Click run script to generate a few random 3d scenes with corresponding depth map. 

This is just a simple stater example, you can then play with the script to randomize the shapes, colors, locations, surface properties etc..


