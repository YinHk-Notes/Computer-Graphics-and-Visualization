## Displacement Maps

Displacement maps **physically displace (as the name implies) the mesh to which they are applied**. In order for detail to be created based on a displacement map, usually the mesh **must be subdivided or tessellated** so real geometry is created. 

The great thing about displacement maps is that they can actually be either baked from a high resolution model or painted by hand. Like a bump map, a displacement map consists of **grayscale values**.


> Now, here’s the not so great thing about displacement maps. Creating all that additional geometry in real time is extremely difficult and hard on your system. Because of this, most 3D applications calculate final displacement results at render time. 
> In comparison to bump or normal maps, a displacement map will also add significant time to your renders. As a result of this additional geometry, it’s hard to beat the results of a displacement map. Since the surface is actually modified, the silhouette reflects the additional geometry. You should always weigh the expense of a displacement map against the added benefit before deciding to use one.




### ref 
https://www.pluralsight.com/blog/film-games/bump-normal-and-displacement-maps


