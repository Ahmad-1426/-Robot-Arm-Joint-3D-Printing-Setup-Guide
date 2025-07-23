# Robot Arm Joint 3D Printing Setup Guide

This document outlines the steps for preparing the robot arm joint model for 3D printing, recommends the ideal filament, and shows how to upload everything to GitHub.

---

## 1. Export the Model as STL  
1. Open your original CAD project (e.g., SolidWorks or Fusion 360).  
2. Choose **Export** or **Save As**.  
3. Select the **.STL** format and save the file as `robot_arm_joint.stl`.

---

## 2. Load the STL into Your Slicer  
1. Launch AnkerMake Studio (or Cura/your preferred slicer).  
2. From the menu, go to **File → Open** and select `robot_arm_joint.stl`.  
3. You should now see the joint displayed on the build plate.
![صورة المفصل على ankermake](https://github.com/user-attachments/assets/6f1cbf6b-4b97-4d5b-be97-a10f29408240)



## 3. Apply These Basic Print Settings  
- **Layer Height:** 0.15 mm  
- **Wall Line Count:** 3  
- **Infill Density:** 20 %  
- **Support:** Enable **Tree Supports** with a 50° overhang threshold  
- **First Layer Speed:** 20 mm/s  



## 4. Choose the Right Filament  

**Recommended Material:** PLA+ (AnkerMake PLA+ Basic)  
**Key Advantages:**  
- **Higher strength** vs. standard PLA, with better stress resistance.  
- **Low shrinkage** to minimize warping.  
- **Fast cooling** for sharper details and cleaner bridges.  
- **Easy to store** in a sealed container to prevent moisture uptake.

---


---

