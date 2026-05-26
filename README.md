# OpenGL Shader Sandbox

A testing ground for low-level graphics programming. It provides af flexible environment focused on rendering architecture and real-time GLSL experiments.

## Features
* Custom GLSL Sandbox: live-compilation inspired by [ShaderToy](https://www.shadertoy.com/)
* Visual Node Graph: built with [ImNodes](https://github.com/Nelarius/imnodes) to manage simple rendering logic
* Experimental Focus: shaders, 3D pipelines and software architecture

## Editor Showcase
<p><img src="imgs/image.png" width="420" /> <img src="imgs/image1.png" width="420" /></p>

## Build Instructions
1. Clone the repository
2. Open `Shader Experiments.sln` in Visual Studio (2019/2022)
3. Ensure the solution platform is strictly set to **x86**
4. Verify the linker paths for local dependencies (assimp, glm, glew)
5. Ensure SDL2 is located at `C:\SDL2` (or manually update)
6. Build and run

## Tech Stack
* Core: C++, OpenGL
* Window & Context: SDL2
* Interface: Dear ImGui, ImNodes
* Math & Assets: GLM, Assimp


## Shader Experiments
<p align="left">
  <img src="imgs/{F1CC867A-E17B-48C1-A282-DA0DAF45D197}.png" width="270" />
  <img src="imgs/{F06D9686-4E0F-48CB-9F4E-57F827ECE27B}.png" width="270" />
  <img src="imgs/{C4C3D986-2DA9-4520-B07E-95B5731EFC55}.png" width="270" />
  <br>
  <img src="imgs/{99D0C62E-F2EB-464B-BCEE-F867E84A79E3}.png" width="270" />
  <img src="imgs/{E88E2862-2B30-4F1D-ACCE-06E0F925CBFC}.png" width="270" />
  <img src="imgs/{859B2631-9728-4190-B7F6-F06DCFEB44CB}.png" width="270" />
  <br>
  <img src="imgs/{A538B882-6DDD-4E21-926F-A3BC33378370}.png" width="270" />
  <img src="imgs/{1D49D9A-4CCF-43F0-9ED4-31AACB969A0F}.png" width="270" />
  <img src="imgs/{8D9463B4-214B-47DD-97AD-25D7F4CA4F13}.png" width="270" />
</p>

