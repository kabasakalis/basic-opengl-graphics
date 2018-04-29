# BasicGraphics
### Basic demo for OpenGL on Windows 10


[Instruction on how to compile dependencies](https://web.cs.sunyit.edu//~realemj/guides/installGraphics.html)

=============

The dependencies are all compiled according to the instructions and installed in my DropBox folder named OpenGl.
I use a symbolic link from the root of the project to my Dropbox folder (see .gitignore). When I configure the 
project with CMAKE I specify this OpenGl folder path as the MASTER_DEPEND variable.

This is a very basic OpenGL sample for use in SUNY Polytechnic Institute's CS 450/548 Computer Graphics course.  It has the following dependencies:

- OpenGL
- GLFW
- FREEGLUT (GLFW alternative)
- GLEW 
- Glad (GLEW alternative)
- GLM
- Assimp
- stb_image
- stb_image_write



The shaders are set up to work with OpenGL version 3.3.

When running, it should display a window with a darkish green background with a green square in the upper-left corner,
a blue square in the upper-right corner, and a red square in the lower-left corner.  When the left mouse button is pressed, a small white square will follow the mouse.

