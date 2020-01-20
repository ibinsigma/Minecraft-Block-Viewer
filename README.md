# Minecraft Block Viewer
An interactive application developed using OpenGL and C++ to view and interact with Minecraft blocks.

The purpose behind the developement of this project was solely learning Computer Graphics and getting used to the OpenGL library.

#### Preview
<p align="center">
    <img src="https://drive.google.com/uc?export=view&id=1nbPvCFZ0iK6C_sT1JNBE-XEGoEx9WKwc" height=250>
    &nbsp;&nbsp;
    <img src="https://drive.google.com/uc?export=view&id=1wLdfYx9zQe8cHwNv39qQYqocJyRpAQ-H" height="250">
    <br>
    <i>Block textures redered using OpenGL with diffuse and specular maps</i>
</p>

#### Features
- Enable/disable lights
- Phong Lighting
- Rendering transparent/translucent object
- Block hover animation
- Multiple texture faces
- Specular and Diffuse maps

#### Build instructions
Run the following script in the project folder to fetch block texture atlases
```bash
./fetch_textures.sh
```

Build the project
```bash
mkdir build
cd build
cmake ..
make
```

Run the program
```bash
./minecraft_block_viewer
```

##### Controls
| Key        | Description              |
| ---------- | ------------------------ |
| PageUp     | Switch to next block     |
| PageDown   | Switch to previous Block |
| L Key      | Toggle Lighting in scene |
| Mouse Hold | Break Block              |
| Escape key | Exit                     |
| Arrow Keys | Rotate Block             |