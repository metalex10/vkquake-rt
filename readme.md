# Quake: Ray Traced

Quake: Ray Traced adds a path tracing renderer to id Software's [Quake](https://en.wikipedia.org/wiki/Quake_(video_game)) using the [RayTracedGL1](https://github.com/sultim-t/RayTracedGL1) library.

Quake: Ray Traced is based on the [vkQuake](https://github.com/Novum/vkQuake) — a port of QuakeSpasm to Vulkan API.

## Build

### Windows

Clone the vkQuake repo from `https://github.com/sultim-t/vkquake-rt.git`

Prerequisites:

* [Git for Windows](https://github.com/git-for-windows/git/releases)
* GPU with a ray tracing support

Steps:

* Install [Visual Studio Community](https://www.visualstudio.com/products/free-developer-offers-vs) with Visual C++ component
* Open the Visual Studio solution, `Windows\VisualStudio\vkquake.sln`
* ~~Build the [RayTracedGL1](https://github.com/sultim-t/RayTracedGL1/tree/quake) library, provide its header files / `.lib` to the `vkQuake` solution~~
This is not neccesary anymore
* Build the `vkQuake` solution
* Copy `RayTracedGL1.dll` next to `vkQuake.exe` before running the executable

if is neccesary, download this sh*t and unpack on you Quake folder, If possible, it should work on the Steam installation; I'm not sure if it will work in other installations or versions, it only works in the rerelease version.

It does not contain any .pak files; you must add these from your purchased version of Quake 1!!!!!!!!!!

https://www.mediafire.com/file/rmpun1bko5fyi0a/Quake+wtout+pak+files.rar/file
