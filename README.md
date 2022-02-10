# Line Intensity Profile Analysis of Medical Images using Slicer

# Goal

Aim of the ‘Line Intensity Profile’ extension is to plot intensity levels of pixels within a drawn line. This extension can be used to compare the noise levels of multiple images and to compare physical properties of a drawn line in two 3D images. Potential applications of the extension are : Intensity homogeneity correction and change characterization.

# Requirements

1. **Slicer software**

Slicer is a free and open source platform for analyzing the medical images such as MRI, CT, etc. 

Download stable version of slicer from [download.slicer.org](http://download.slicer.org) depending on your operating system.

2. **Python**

# Installing Extension to Slicer

1. Download the zip file and extract it
2. Install `DeveloperToolsForExtensions' from extension manager. 
3. Restart the Slicer
4. Open the Developer tools for extensions extension
    
    Modules → Developer tools → Developer tools for extension
    
5. Load the LineIntensityProfile.py python file
    
    Load Module → Select LineIntensityProfile.py (from downloaded folder)
    
6. Open Line Intensity Profile extension and explore.
    
    Module → Examples → Line Intensity Profile


# Instructions (Step-by-Step)

1. **Load the `Line Intensity Profile' Extension**
    
    Modules → Examples → Line Intensity Profile
    
    ![Figure 1 : Widget Elements of Line Intensity Profile Extension](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/1.png)
    
    Figure 1 : Widget Elements of Line Intensity Profile Extension
    
2. **Click on `Reload and Test' to test the functionality of the extension.**
    
    Two sample volumes (MRIBrainTumor1 and MRIBrainTumor2) and a ruler are initiated on predefine position.
    
    You should be able to see the ruler and the line intensity plot - as shown below.
    
    ![Figure 2 : Line Intensity plot and ruler positioning during testing of extension.](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/2.png)
    
    Figure 2 : Line Intensity plot and ruler positioning during testing of extension.
    
    ![Figure 3 : Line intensity profile during test run.](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/3.png)
    
    Figure 3 : Line intensity profile during test run.
    
    ![Figure 4 : Test Ruler placement on both volumes](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/6.png)
    
    Figure 4 : Test Ruler placement on both volumes
    

**3. Use sample data (or own data) to explore the extension.**

1. Load sample data
    
    Module Finder → Sample data → Select any two built in data
    
    e.g.: (CTchest and CTA cardio) or (MRBrainTumor1 and MRBrainTumor2)
    
2.  Load the Line Intensity Profile extension
    
    Modules → Examples → Line Intensity Profile
    
3. Select appropriate volume nodes.
4. Select Ruler from the toolbar (mouse interaction)
    
    ![Figure 5 : Ruler in the toolbar ](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/7.png)
    
    Figure 5 : Ruler in the toolbar 
    
5. Place the ruler in the region of interest (in any one image - axial/ sagittal/ coronal view)
    
    Here ruler is placed in sagittal view - Line intensity profile of drawn line is shown below.
    
    **MRBrainTumor1 and MRBrainTumor2**
    

![Figure 6 : Line Intensity Profile of user drawn line (Axial view)](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/10.png)

Figure 6 : Line Intensity Profile of user drawn line (Axial view)

![Figure 7 : Line Intensity Profile of user drawn line (Sagittal view)](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/8.png)

Figure 7 : Line Intensity Profile of user drawn line (Sagittal view)

![Figure 8 : Line Intensity Profile of user drawn line (Coronal view)](Line%20Intensity%20Profile%20Analysis%20of%20Medical%20Images/9.png)

Figure 8 : Line Intensity Profile of user drawn line (Coronal view)

# Acknowledgment

I would like to express my special thanks of gratitude to Dr. Nuwan Dayananda, Dr. Ranga Rodrigo and Mr. Achintha Iroshan, who gave me the golden opportunity to work on development of line intensity profile using Slicer. 

# Reference

[Developing extension in 3D Slicer](https://docs.google.com/presentation/d/1JXIfs0rAM7DwZAho57Jqz14MRn2BIMrjB17Uj_7Yztc/htmlpresent)
