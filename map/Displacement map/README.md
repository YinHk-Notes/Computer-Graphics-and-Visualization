## Displacement Maps

Displacement maps **physically displace (as the name implies) the mesh to which they are applied**. In order for detail to be created based on a displacement map, usually the mesh **must be subdivided or tessellated** so real geometry is created. 

The great thing about displacement maps is that they can actually be either baked from a high resolution model or painted by hand. Like a bump map, a displacement map consists of **grayscale values**.


> Now, here’s the not so great thing about displacement maps. Creating all that additional geometry in real time is extremely difficult and hard on your system. Because of this, most 3D applications calculate final displacement results at render time. 
> In comparison to bump or normal maps, a displacement map will also add significant time to your renders. As a result of this additional geometry, it’s hard to beat the results of a displacement map. Since the surface is actually modified, the silhouette reflects the additional geometry. You should always weigh the expense of a displacement map against the added benefit before deciding to use one.


置换贴图焕发了纹理的生机:  

- 阴影
- 细节更丰富
- 轮廓线
- 更好的深度感

置换映射是一种有别于视差映射, 法线映射和凹凸映射的纹理制作方法, 因为其利用的是带纹理的曲面上的点(网格)的置换来创建一种有深度有起伏的效果.也就是说, 您在对象上设置的多边形会根据高度贴图或深度贴图来移动. 


> 置換貼圖是使用高度圖將經過紋理化的表面上實際幾何點位置**沿著表面法線根據保存在紋理中的數值進行移位**的技術


### ref 
https://www.pluralsight.com/blog/film-games/bump-normal-and-displacement-maps

https://zh.wikipedia.org/wiki/%E4%BD%8D%E7%A7%BB%E8%B4%B4%E5%9B%BE

https://3dcoat.com/cn/articles/article/displacement-map-in-3dcoat/
