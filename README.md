# Ex. No. 7 - SIMULATION OF PRE PROCESSING IN ADDITIVE MANUFACTURING
### DATE: 
## AIM:
### To simulate the Pre Processing for 3D printing.

## REQUIREMENTS:
### System - Windows 7 or higher, 1 GB RAM.

## PROCEDURE:
### Pre-processing encompasses the steps between design and printing. Process of 3D printing starts with designing in CAD. Then printer software slices 3D CAD file into layers. For each slice, the software converts the data into machine code that determines tool paths for the machine to follow. The various steps in pre-processing from design to printing are as follows:

### 1)	CAD File
### 2)	Conversion to STL a. Orientation b. Support Structure c. Slicing d. Path Planning

### 1. CAD File
### Every manufacturing process starts with the process of designing and as in any type of manufacturing, there are certain limitations to the materials and manufacturing processes that dictate how the product should be designed, 3D printing is no different. In 3d printing, characteristics of hardware, software, temperature, filament and many other factors play an important role in how a digital model translates into a printed object. Some of them are designed with a strong base, grain direction, overhung, wall thickness, round corners and tolerances.

### 2. Conversion to STL
### In order to check the interface of the object and make it reliable to 3d printers, conversion to STL file is required. It also facilitates other features like quick error check, bridging the gap between CAD platforms, exhibition purposes and 3D digitizer extension.

### a. Orientation:
### Orientation plays a vital role in the final product of 3d printing as it affects the part accuracy, manufacturing time, strength and surface finish. There are various orientations by which we can print the object such as vertically upward, vertically downward and in horizontal plane.

### b. Support Structure:
### Support structures are required where the objects are unable to get printed directly. Support structures help to guarantee the printability of a section during the 3D printing measure and also it can assist with forestalling part twisting, secure a section to the printing bed and guarantee that parts are joined to the fundamental body of the printed part.

### c. Slicing:
### The motive behind slicing a 3D model is to transform the model into guidelines for the 3D printer. To play out this errand, the slicing software isolates the item into numerous layers. It's classified "slicing" since it "slices" the 3D model to make numerous layers. After the layers have been made, the slicing software applies different qualities to every one of them.

### d. Path Planning:
### Path planning helps to improve the printed surface quality, shape accuracy and infill distribution quality. There are various ways for path planning which can be used to print the objects which may affect the following factors in objects like raster path, grid path, spiral path and zigzag path.

![image](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/baef8515-67d7-4c96-accc-4ee88035c9e7)

### ●	All the processes related to pre-processing will be shown on the screen.
### ●	Select CAD file preparation from the visible list.
### ●	When the first process is selected then it will open in the blank space in the left side of the screen.
### ●	Select the options of process of pre-processing in the sequence in which they are shown.
### ●	If the user follows an incorrect sequence then a pop-up will appear on the screen showing the name of the process to be selected.

## OUTPUT:

### Name: SRINITHI V
### Register Number: 212222110046

### 1. CAD File Preparation

![ex 7 1](https://github.com/SrinithiV/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118722030/1efa08df-b575-4311-bdd6-10913467572e)

#### The first step in pre-processing is preparing the design of the object to be printed. This typically involves using computer-aided design (CAD) software to create a 3D model of the desired object. The design can be created from scratch or obtained from an existing design library.

### 2. Conversion to STL

![ex 7 2](https://github.com/SrinithiV/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118722030/ac8cfd1b-a801-4f7e-8f1d-e241505cf300)

##### The conversion of a CAD file to the STL (Standard Tessellation Language) format is a common step in the pre-processing phase of 3D printing. STL files represent the 3D geometry of an object as a collection of interconnected triangles, making it suitable for 3D printing. To convert a CAD file to STL, follow these general steps:

### a. Orientation:

![ex 7 3 ](https://github.com/SrinithiV/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118722030/782e6649-104a-4a9e-b93c-706218be50f4)

##### Orientation is defined as the alignment of an object within the space of the build volume. It impacts stability, surface finish, and printability.
   ##### Horizontal Orientation :  In this orientation, the bottom surface of the object is placed flat on the printing bed. This is often the default orientation for many objects, especially those with a stable base. It provides good stability during printing and minimizes the need for support structures, resulting in a better surface finish on the bottom side.
   ##### Vertical Orientation :  Vertical orientation involves standing the object upright on its largest flat surface. This can be useful for objects that require maximum strength in a particular direction or have long vertical features. However, it may require additional support structures for overhangs or delicate parts.
   ##### Angled Orientation :  Angled orientation refers to positioning the object at an angle between horizontal and vertical orientations. This can be beneficial for reducing the number and complexity of support structures while maintaining good strength and surface quality. Angling the object can also help minimize visible layer lines on critical surfaces.
 
### b. Support Structure:


##### Support structures are temporary structures that are added to a 3D printed object during the printing process. They are designed to provide stability and prevent the collapse or distortion of overhanging or complex features of the model that do not have sufficient support from the layers below.

### c. Slicing:



##### Slicing in 3D printing is the process of converting a 3D model into a set of instructions that a 3D printer can understand and execute. It involves breaking down the model into thin, horizontal layers (slices) and generating the necessary toolpath instructions for the printer to create each layer.
   ##### Uniform Layer Slicing :  Uniform layer slicing, also known as fixed layer thickness slicing, is a traditional method where the 3D model is sliced into a series of uniformly thick layers. Each layer has a constant thickness throughout the entire print. This slicing technique is straightforward and commonly used in many 3D printing applications. 
   ##### Adaptive Layer Slicing :  Adaptive layer slicing, also referred to as variable layer thickness slicing, is a technique that adjusts the layer thickness based on the complexity and curvature of the 3D model. In this approach, the slicing software analyzes the model and determines the appropriate layer thickness for different regions of the object.
   ##### Curved Layer Slicing :  Curved layer slicing, sometimes called continuous surface slicing or non-planar slicing, is an advanced technique that aims to reduce or eliminate the visible stair-stepping effect on curved surfaces. Instead of slicing the model into flat layers, this method follows the curvature of the object, generating curved layers that align with the surface. By adapting the layers to the object's shape, curved layer slicing can result in smoother and more accurate representations of curved surfaces.

### d. Path Planning:



##### Path planning, in the context of 3D printing, refers to the process of determining the optimal toolpath or trajectory for the 3D printer's extruder to follow while building each layer of the printed object. It involves calculating the most efficient and effective path for the printer's nozzle or extruder to deposit material accurately and smoothly.

## Result: 
### Thus the simulation on the Preprocessing in additive manufacturing is completed.
