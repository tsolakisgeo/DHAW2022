---
class: 18
day: Wednesday, November 9
title: 'Blender (1/2)'
tags: 
---

## Assignment due: 
- SQL query: Create an ordered list with the city of each province that has the most monuments along with the counts of the monuments.

## Before Class 
- Download [Blender](https://www.blender.org/download/)

## Notes 

#### Blender shortcuts
- Shift + A: Add
- Tab: Swift between Object Mode and Edit Mode
- Shift + R: Repeat

#### Creating a 3D model of Crete

##### QGIS
- First, you have to export two images from QGIS. Select a layer with elevation data and another with 
- Project -> Import/Export -> Export map to image (choose 1200 dpi)

##### Open Blender
  - Select and delete the cube
  - Select and delete the light
  - Shift + A -> Mesh - Plane
- Go to Edit Mode
  - Right click on the place and Subdivide
  - Repeat (several times) with Shift + R
- Return to Object mode
- Modifier (looks like a wrench)
  - Add modifier -> Difform -> Displace
  - New
  - Srength 0.05
  - Midlevel 0.1
- Texture properties
  - Open and Choose the elevation .jpg
  - 
- Modifier
  - Add modifier -> Generate -> Subdivision surface
  - Right click on the object and Shade smooth

- Materials tab
  - New
  - In base color click the dot. Image texture. Open the second .jpg file you exported.

- Choose amonge the spheres above the nagivation tools, the Display render preview (the one on the right)

#### Blender tutorials
- [Reconstructing archaeology Baalshamin temple (Palmyra) in Blender](https://www.youtube.com/watch?v=XfRsfwipq_0)
- [How to Create 3D Terrain with Google Maps and Blender!](https://www.youtube.com/watch?v=Mj7Z1P2hUWk&ab_channel=CGGeek)
- [Blender GIS - introduction and complete workflow](https://www.youtube.com/watch?v=u8Fg-u-VWUE)
