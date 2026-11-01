<div align="center">

## [3D Engine](https://github.com/EggyStudio/3DEngine)

A C# engine on SDL3, Vulkan, ImGui and Slang. Raylib's design over a Bevy-style ECS and scheduler,
scripted with its own Unity-style behaviors. Implementing Radiance Cascades. [e3d.cs]

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4)
![Graphics](https://img.shields.io/badge/Graphics-Vulkan-AC162C)
![Windowing](https://img.shields.io/badge/Windowing-SDL3-0B7BB2)
![Shaders](https://img.shields.io/badge/Shaders-Slang-2E7D32)
![Status](https://img.shields.io/badge/Status-Early-yellow)

<img src="https://raw.githubusercontent.com/EggyStudio/Voxel-Sandbox/main/.github/assets/head.gif" width="800" height="450" alt="Ten views of seeds 1 and 6 two seconds each, a desert village, the badlands, a cherry grove, a plains village by its river, a swamp, the jungle, a snowy village by day and by night, a room lit by a lantern and torches, and the sun rising over the sea">

[Voxel Sandbox](https://github.com/EggyStudio/Voxel-Sandbox) - A voxel game written in C# on 3DEngine. Implementing Radiance Cascades. [e3d.cs]

</div>

<div align="center">

## [Bevy C#](https://github.com/EggyStudio/BevyCSharp)

Bevy C# [Behavior] on a struct are component & systems, generated at compile or runtime and wired straight into Bevy's ECS. Implementing Radiance Cascades. [bcs]

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4) ![Graphics](https://img.shields.io/badge/Graphics-wgpu%20%28Vulkan%2C%20DX12%2C%20Metal%29-AC162C) ![Windowing](https://img.shields.io/badge/Windowing-winit-0B7BB2) ![Shaders](https://img.shields.io/badge/Shaders-Slang-2E7D32) ![Status](https://img.shields.io/badge/Status-Early-yellow)

![Showcase](https://raw.githubusercontent.com/EggyStudio/BevyCSharp/refs/heads/main/.github/assets/showcase_3.gif)


</div>

## The modules both engines use

Libraries the engines take as git submodules, so one solution serves both.

- [Modeling](https://github.com/EggyStudio/Modeling) - An edit mesh shaped by operations through a selection, with recipes and commands
- [Vegetation](https://github.com/EggyStudio/Vegetation) - Trees and grass grown from a species and a seed, with their texture sets and placement
- [Levels](https://github.com/EggyStudio/Levels) - Levels in the Valve 220 map format, brushes to meshes and collision, with TrenchBroom's files
- [Landscape](https://github.com/EggyStudio/Landscape) - A heightfield shaped by stamps and erosion, with vegetation placed over it
- [Sky](https://github.com/EggyStudio/Sky) - The sky's clock, the sun's and the sky's light in physical units, the atmosphere's parameters, the weather and the looks by the sun's height, both engines lighting from its numbers while each draws its own sky
- [RadianceCascades](https://github.com/EggyStudio/RadianceCascades) - The radiance cascades' CPU side and Slang shaders, each engine binding its own GPU side
- [Tools](https://github.com/EggyStudio/Tools) - The scripts and document sources the repositories share, the devlog generator and the run reader among them

## Linux

- [02Gnome](https://github.com/EggyStudio/02Gnome) - Configure and customize your GNOME environment in one command

## .NET bindings and tools

- [UniversalSceneDescription](https://github.com/EggyStudio/UniversalSceneDescription) - OpenUSD USD.NET (Universal Scene Description) by Pixar and translated by Unity
- [MaterialX.Net](https://github.com/EggyStudio/MaterialX.Net) - A single-package .NET binding for the MaterialX rich material and look-development content in computer graphics
- [UltralightNet.Bundle](https://github.com/EggyStudio/UltralightNet.Bundle) - A single-package .NET binding for the Ultralight HTML rendering engine

## [Unity Essentials](https://github.com/EggyStudio/UnityEssentials)

A modular package ecosystem for Unity 6 and HDRP, production-ready building blocks for game and simulation development, from core architecture and environment systems to graphics, networking and editor tooling. Each module installs on its own, and the dependencies between modules resolve automatically. All scripts live in the `UnityEssentials` namespace.

**Installation**

1. Add the package through Unity's Package Manager, in the Window menu, with the plus button and "Add package from git URL", pasting

   ```
   https://github.com/EggyStudio/UnityEssentials.git
   ```

2. Install modules from the Tools menu, under UnityEssentials and Install & Update. Select single modules or install all, and run it again at any time to update.
