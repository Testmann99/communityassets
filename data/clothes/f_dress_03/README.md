# F Dress 03

* Author: Mindfront
* Category: Gown/Robe
* Compatibility: 1.1.x
* License: CC-BY

Tags: Female, Elegant.
My interpretation of a vintage weddingdress. I am experimenting on making more advanced clothes.
The dress will look totally weird in some cases. Some areas may overlap each other, especially on the skirt.
I tried to make the belt buckle more static to avoid strong deformation.

The flower pattern have some mismatching areas but it shouldn't be noticeably.

It could be tricky to correct ugly deformation as the dress consists of several different parts on top of each other.
If you use Blender, use the Sculpt Mode with Clay and Smooth brush at low strength to adjust deformation and fitness.

In Blender Cycles the inside of the lace fabric become black due to the normal map, one way, I found, to correct this is by using the nodes
"Geometry" and "MixRGB". Set the MixRGB lower color slot to 0.5 0.5 1.0. Then put the output from the normal map node to the upper color slot and connect the Geometry node output "Backfacing" as the MixRGB factor and connect the output of MixRGB into the normal input of the shaders. That makes the normal map neutral and not visible on the the fabric inside.

![Example](F_Dress_03_PIC.png)

