# PVS-Studio CMake Module

PVS-Studio CMake module (**PVS-Studio.cmake**) can be used to integrate [PVS-Studio](https://www.viva64.com/en/pvs-studio/) analysis into CMake-based C and C++ cross-platform projects under Windows, Linux and macOS. This integration is generally build-system independent, however, several specific options work only under certain CMake generators. You can also use build-system specific analyzer integration (for example, [PVS-Studio_Cmd for MSBuild](https://pvs-studio.com/en/docs/manual/0035/) projects under Windows), or integrate the analyzer [directly into a build system](https://pvs-studio.com/en/docs/manual/0006/).

PVS-Studio CMake module uses the `pvs_studio_add_target` function to add a custom PVS-Studio target, which will be used to run the analysis. The detailed description of all available parameters of `pvs_studio_add_target` function is available at [this link](https://pvs-studio.com/en/docs/manual/6591/).

You can also perform analysis of C and C++ projects based on [JSON Compilation Database](https://pvs-studio.com/en/docs/manual/6557/).
