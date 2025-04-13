# GraphicsEngine

Created with the openFrameworks tools, using the ofxAssimpModelLoader and ofxGui addons.

Link to showcase: https://youtu.be/8Q_9dQ-k2Z0

A school project made with 3 other students, its goal was to create multiple functions of modern graphics engines from scratch to familiarize ourselves with the subject.

The functions that were implemented in this project are:
  - Engine Interactions:
    - An interface and scene graph.
    - A camera which can be moved or zoomed and render perspective or orthographic projections.
  - Images:
    -  Importing images into the engine to be manipulated or upon which various filters can be applied, from a simple color filter to applying a convolution matrix to the image.
    -  Exporting the current screen space as an image or a series of images.
  - Manipulation of 2D and 3D primitives:
    -  Instantiating vector primitives, such as primitive shapes and Bézier curves while being able to modify their color and line properties via drawing tools as well as interactively transform or animate them afterwards.
    -  Instantiating 3D primitives like a cube or sphere.
    -  Parametric Curves following either the Catmull-Rom or Hermite’s curve can be drawn in the scene.
    -  Similarly, Parametric Surfaces can be instantiated to create a Coons patch.
    -  Create a mesh following the Delaunay Triangulation algorithm.
  - 3D Models:
    -  Show 3D models under different rendering types, such as Fill Render, Wireframe Render or Vertex Render.
    -  Apply image textures on a model with texture coordinates as well as modifying them via Tone Mapping and by manipulating their Metallicity and Roughness properties.
    -  Models can be further modified by applying customizable materials.
  - Lighting:
    - Choice of illumination models between Lambert, Gouraud, Phong and Bling-Phong models.
    - Light sources can be instantiated in the scene and manipulated from the following:
      - Ambient
      - Directionnal
      - Area
      - Spotlight
      - Point
  - Shaders:
    - A procedural texture can be applied to the primitives which is modified by its own shader.
    - A lighting shader can be activated to calculate the result of multiple lights on the same vertex/fragment.
  - Raycasting:
    - Render a scene using Raycasting, which includes reflective and refractive surfaces.
  
