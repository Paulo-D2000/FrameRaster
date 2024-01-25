# FrameRaster 

#### Deps Setup (Linux x86_64)

Install X11 deps...

`sudo apt install libxi-dev libcursor-dev libxinerama-dev`

Install vulkan tools and try running `vulkan_info`, then `vkcube`. If successfull your machine supports Vulkan, proceed...

`sudo apt install vulkan-tools`

Install the Vulkan library...

`sudo apt install libvulkan-dev`

Then install spirv-tools

`sudo apt install vulkan-validationlayers-dev spirv-tools`

#### Build

`git clone ...`
`cd FrameRaster`
`mkdir build`
`cd build`
`cmake ..`
`make`