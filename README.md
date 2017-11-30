
# The Blender Character Creator
Our Udemy course will teach you all you need to know to create rigged characters for video games.

You're welcome to download, fork or do whatever else legal with all the files!

## How To Use These Files
You can download the latest state of this section, or go to **Commits** then download to get our project as it was at the end of any lecture.

# Section 3 Cube Dude
Keeping it simple we are going to make a simple character that is textured and fully rigged (Reference: CD_BCC)
Here are the lectures of the course for this section...

### 1 Introduction to Section 3
+ Michael welcomes you to and introduces what is coming up in Section 3

### 2 Importing Reference Material
+ There are several methods
+ Each has it's advantages and draw backs
+ Background images
+ Importing images as planes
+ Loading an image in the UV Image Editor

### 3 Object Mode And Edit Mode
+ The difference between Mesh Data and Mesh objects
+ Models can be made separately and joined
+ When to multiple mesh objects
+ Linked mesh data
+ Remember to Edit in edit mode, saves many headaches later.

### 4 Intersecting Geometry
+ Intersecting geometry good / bad
+ Angle makes a difference Z buffer distance
+ Closing Meshes
+ Animation can expose flawed areas
+ Linked Mesh Data

### 5 Creating New Geometry
+ Extruding
+ Insetting
+ Bevelling a vertex
+ Keep an eye out for double extrudes
+ Removing doubles
+ Deleting Loose Geometry

### 6 Adjusting Geometry
+ Loop Cut and Slide
+ Transforms
+ Edge Slide
+ Aligning with other mesh data, Snapping

### 7 The Mirror Modifier
+ Making everything separate and joining at the end works
+ Using the mirror modifier
+ Understanding reflection axes
+ Using clipping and merge options
+ Common mirror modifier pitfalls

### 7a Checking An Exported Model (In Unity)
+ Quickly check our model looks as expected externally to Blender

### 8 Quick Texturing Our Model (Blender Render)
+ After modelling is completed texturing can be done
+ Paint in the 3D window
+ Quick texturing methods

### 9 UV Unwrapping Overview
+ Smart UV Project
+ Seams
+ You can add mesh data to a mesh object but you might need to unwrap again an possibly re texture if you do that!

### 10 Optimising A UV
+ Controlling the UV layout
+ Alter the UV layout
+ Look at different ways to optimise
+ Packing islands
+ Understanding island margins

### 11 Creating A Texture
+ Painting in the UV/Image Editor
+ Applying materials to a model
+ Assigning a texture to that material

### 12 Checking Our Texture Works Externally
+ Quickly check our model looks as expected externally to Blender

### 13 Applying Multiple Textures To Our Model
+ Useful If you want to mock something out quickly
+ Works well with broad areas

### 14 Texturing Our Model (Cycles)
+ Brief recap of previous lectures
+ Setting up texture so it is visible in Cycles And Blender Render
+ Switch between Blender Render and Cycles

### 14a Generated Textures
+ Quick to apply to a model
require baking to use outside of Blender

### 14b Masking off Areas when Painting
+ Using Face Masks
+ Using Texture Masks

### 15 Minimum Skeleton Requirements
+ 15 Bones as a minimum
+ Hips are generally the root of the other bones
+ Name bones as you go

### 16 Automatically Linking Our Mesh And Armature
+ Fix bone orientation issue
+ Works great as good first pass
+ Can fail badly too
+ A look at what is going on

### 17 Vertex Groups
+ Understanding it is a way of grouping vertices
+ A Vertex can be a member of more than one group
+ This is used all across Blender not just for armatures

### 18 Checking Your Rig Externally (Unity and Unreal)
+ A Quick check to ensure what we have made is functioning as expected externally

### 19 Spaces
+ A Quick Look at the various spaces you can work in
+ What the difference is between the main two, Global/World and Local

### 20 Limiting Joint Movement
+ Bone Constraints
+ Bone Roll

### 21 Creating Custom Shaped Bones
+ Create different shaped for bones that have a different purpose
+ How to Toggle custom Shapes on and of
+ Reasons for having a custom bone shape

### 22 Inverse Kinematics (IK) Introduction
+ Forward Kinematics (FK) what we have been using know
+ A Mix of IK and FK gives you a productive work flow.

### 23 Adding IK Control Bones
+ Control bones
+ Turn off deforming as they have no direct influence over the mesh
+ Setup IK constraints

### 24 Adding Pole Targets
+ These are another type of control bone which other bones point towards
+ Control Bone- Turn off deforming

### 25 Quickly Mirroring And Renaming Bones
+ Quick way of mirroring your bones
+ Rename Bones from left to right with ease

### 26 Re-Rigging The Model
+ Re link the mesh to the armature

### 27 Extra Control Bones
+ A main placement control bones
+ Parenting of the IK and pole bones
+ Possible re-parenting of the leg and arm chains

### 28 Bone Layers
+ Bones can be moved on top multiple layers
+ More that one bone layer can be shown at a time
+ This help optimise our display so only key bones are on display

### 29 Researching A Walk Cycle
+ Walk around
+ Watch people walking
+ Use a mirror/ reflection
+ 5 Key Stages and then it repeats
+ Contact, Down, Passing, Up and Contact

### 99 New Ideas Below
//// Lecture Plan////



Planning Larger Projects

The Rigify Add-On

Weight Painting
Bendy Bones
Euler Vs Quaternions
Smooth Vs Rigid Binding
Creating Natural Motion
Forward Kinematics


///
Keep Your Models Simple
+ Using Modifiers to aid construction
+ Keep the model low poly for quick changes
+ Subdivision surface modifier Example
+

Swapping Out Items
