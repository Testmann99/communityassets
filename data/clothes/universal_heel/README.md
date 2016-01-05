# Universal Low Poly High heel 10cm

* Author: grinsegold
* Category: Shoes/Boots/Socks
* Compatibility: 1.1.x
* License: CC-BY

This is a template which you can use to create your own shoe design. Just take the shoe into texture paint mode of blender's UV image editor, under the brush-picker change the blend type from "mix" to "erase alpha" and make the upper part of the shoe transparent. Then just switch back to "mix" type and paint whatever straps and leather-parts you wish to have as design (do that in the 3D-viewport in order to paint directly onto the surface of the object). Don't forget to save the modified texture. Instead of hand-painting the texture, you could stencil a fabric-texture onto it. I unwrapped it having that option in mind, in terms of symmetry. As soon as i know how, i will post the corresponding bvh-file which contains the intended foot pose for this high heel. Then you store that file in v1/data/special_poses/foot/. Last step is then to open the mhclo-file in a text editor (like notepad) and adding a line under that one that sais: "material universal_heel.mhmat". In that new line type: "special_pose foot 10cm.bvh" (without ""). Save that file. Done.
Update (03.01.'16): Get the bvh here:
http://www.makehumancommunity.org/forum/viewtopic.php?f=4&t=13036

![Example](Universal_heel_demo.png)

