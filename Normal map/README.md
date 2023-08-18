## Normal Mapping

Normal maps give your object texture and depth by **changing the direction light is reflected off your 3D model**. These are also known as **Bump Maps** because they **make your surface look bumpy**. 

**Normal maps don’t actually change the geometry of your 3D model** so you can’t use them for extreme depth, but they are great to **give realistic textures while keeping the polygon count low**.



**Normal maps** are a type of **Bump Map**. They are a special kind of texture that allow you to add surface detail such as **bumps**, **grooves**, and **scratches** to a model which **catch the light** as if they are represented by real geometry.

In 3D computer graphics, **normal mapping**, or Dot3 bump mapping, is a texture mapping technique used for faking the lighting of bumps and dents – an implementation of bump mapping. It is used to add details without using more polygons. A common use of this technique is to greatly enhance the appearance and details of a low polygon model by generating a normal map from a high polygon model or height map.

**Normal maps** are commonly stored as regular RGB images where the RGB components correspond to the X, Y, and Z coordinates, respectively, of the surface normal.



For example, you might want to show a surface which has grooves and screws or rivets across the surface, like an aircraft hull. One way to do this would be to model these details as geometry, as shown below.


A sheet of aircraft metal with details modeled as real geometry. \
![](./StandardShaderNormalMapBadGeometry.jpg)

Depending on the situation it is not normally a good idea to have such tiny details modelled as “real” geometry. On the right you can see the polygons required to make up the detail of a single screwhead. Over a large model with lots of fine surface detail this would require a very high number of polygons to be drawn. To avoid this, we should use a normal map to represent the fine surface detail, and a lower resolution polygonal surface for the larger shape of the model.

If we instead represent this detail with a bump map, the surface geometry can become much simpler, and the detail is represented as a texture which modulates how light reflects off the surface. This is something modern graphics hardware can do extremely fast. Your metal surface can now be a low-poly flat plane, and the screws, rivets, grooves and scratches will catch the light and appear to have depth because of the texture.

![](./StandardShaderNormalMapAircraftSurface.jpg)

The screws, grooves and scratches are defined in a normalmap, which modifies how light reflects off the surface of this low-poly plane, giving the impression of 3D detail. As well as the rivets and screws, a texture allows us to include far more detail like subtle bumps and scratches.

In modern game development art pipelines, artists will use their 3D modelling applications to generate normal maps based on very high resolution source models. The normal maps are then mapped onto a lower-resolution game-ready version of the model, so that the original high-resolution detail is rendered using the normalmap.

### ref
https://en.wikipedia.org/wiki/Normal_mapping


https://cpetry.github.io/NormalMap-Online/


https://docs.unity3d.com/2018.3/Documentation/Manual/StandardShaderMaterialParameterNormalMap.html
