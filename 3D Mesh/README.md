## 3D Mesh
A 3D mesh is the structural build of a 3D model consisting of polygons. 3D meshes use reference points in X, Y and Z axes to define shapes with height, width and depth.

While it can take large numbers of polygons to make a 3D mesh approach photorealism, these relatively simple shapes allow for faster processing than other techniques, like NURBS, that produce smooth curves. The polygons used are typically quadrangles or triangles; these geometric shapes can be further broken down into vertices in X, Y, Z coordinates and lines.

Most 3D meshes are created by artists using software packages -- commercial suites like Maya, 3D Studio Max or the free open source Blender 3D. When models are created for animation, they require especially careful construction; odd deformations can result unless polygons are carefully laid for continuous edge loops (a system connecting all edges) around areas that will be moved.

3D modeling can sometimes be a smooth process like working with clay. However, the necessity for edge loops often involves methodical and laborious placement of polygons. Some modelling software includes a process for defining the polygon layout separately from making the general shape.

Reality capture, a newer process, creates accurate 3D models from point clouds, collections of 3D coordinates that define the shape of a physical system.

A mesh is a collection of data that describes a shape. In Unity, you use meshes in the following ways:

- In graphics, you use meshes together with materials; meshes describe the shape of an object that the GPU renders, and materials describe the appearance of its surface.
- In physics, you can use a mesh to determine the shape of a colliderAn invisible shape that is used to handle physical collisions for an object. A collider doesn’t need to be exactly the same shape as the object’s mesh - a rough approximation is often more efficient and indistinguishable in gameplay. More info

### What is mesh in modeling?
A mesh model consists of **vertices, edges, and faces that use polygonal representation, including triangles and quadrilaterals, to define a 3D shape**. Unlike solid models, mesh has no mass properties. However, as with 3D solids, you can create primitive mesh forms such as boxes, cones, and pyramids.

