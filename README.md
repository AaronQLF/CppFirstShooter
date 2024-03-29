Models can be created with Blender and then exported as OBJ format for example. Also FBX format works great for me.
The ModelConverter Tool import the Vertices, Indices and the Material from the file(s)(in case of OBJ an extra MTL file will be created and needed
using the Open-Asset-Importer-Library. The tool then exports the data into a custom BMF file. where the data can be loaded by the game faster.

The Game itself use the Library SDL to create a window and OpenGL-context. Also the Library GLEW is used to get the current OpenGL functions.
For the mathematics (Matrices and Vectors) the Library OpenGL Mathematics is used.
used Libaries:

Assimp for model loading and converting
https://www.assimp.org/
https://github.com/assimp/assimp

SDL for creating a window and the OpenGL-Context
https://www.libsdl.org/

OpenGL for rendering 3D objects
https://www.opengl.org/
https://github.com/topics/opengl

GLEW for easier handling of new OpenGL functions
http://glew.sourceforge.net/
https://github.com/nigels-com/glew

GLM for the matrices/vector calculations
https://glm.g-truc.net/0.9.9/index.html
https://github.com/g-truc/glm

stb for loading fonts and textures/images
https://github.com/nothings/stb
https://github.com/nothings/stb/blob/master/stb_image.h
https://github.com/nothings/stb/blob/master/stb_truetype.h

TinyXML2 for parsing the level-file
https://github.com/leethomason/tinyxml2

irrKlang for 2D and 3D audio
https://www.ambiera.com/irrklang

used Textures from:
https://3dtextures.me
