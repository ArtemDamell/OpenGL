# OpenGL
## OpenGL Rendering in C++

This program is a basic OpenGL program that creates a textured cube. It includes standard headers for C and C++ libraries, as well as libraries for OpenGL and GLFW. It also includes a shader program and a texture.

The main() function initializes GLFW, sets up the window, and initializes GLEW. It then sets up the background color and enables depth testing. It generates a vertex array and creates and compiles the shader program using LoadShaders.

It then sets up the "MVP" uniform and creates the projection matrix, view matrix, and model matrix. It loads the texture using loadBMP_custom and sets up the "myTextureSampler" uniform.

Finally, it sets up the vertices for the cube and renders the cube with the texture using glDrawArrays.
