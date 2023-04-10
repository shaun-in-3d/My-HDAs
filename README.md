# My-HDAs
Houdini digital assets I've made 

SOPS
cone-geo - Cone Generator
- 1.0: A basic cone setup, allows for control over radius, height, number of segments.
- 1.1: added option to set direction via vector and shape with curve

chimneys-geo - Chimney Generator
- 1.0: Generator to add a row of UK style chimneys to isolated faces. note: Chimneys are vertical not guided by nodes (you know like a real chimney). Currently only generates higher res geo


Stylized assets
Grass  ~~patch~~ tuft:
1.0 Basic version that uses rings of circles as points to generate tufts of grass
1.2 Improved on the basic version with new options and the ability to place a flower in the center of the tuft
2.0 Recreated the network to use more Vex: resulting in more organic sprouting area, finer control over scale and bend, also much more efficient.

Mountain Gen
1.0 A generator for stylized mountains that includes snow. Allows you to modify mountain shape via scale and noise, ramps allow for control over where snow falls (eg. how far from top and bottom).

(note: improve this by linking voxel size to overall size so it doesnt get expensive with huge mountains)
