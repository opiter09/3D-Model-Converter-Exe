# 3D Model Converter

Hi, forker here, I added the exe for convenience. Just download that, drag and drop your .fbx onto it, and it will yield a .c3m. That can then plug nicely into the Sonic Adventure repo mentioned below, if you want to work off that to make whatever: https://github.com/Mythical-Atlas/Sonic-Adventure-3DS


This program is closely tied with the Sonic-Adventure-3DS repository. The purpose of this program is to convert fbx 3d model files into a custom format. The reason this is necessary is because it is difficult to implement a library to read fbx files in the workspace I am using to compile for 3ds. Instead of loading an fbx file on the 3ds, this program converts it to a custom format that is simpler to load on the 3ds. It also supports exporting to a C header file, which is useful for small files or debugging, but is inconvenient for large model files because it significantly increases compile time. 
