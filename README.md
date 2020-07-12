### This project is under development and will see changes

# Vulkan SDK Examples and Demos
The idea behind this project is to create a comprehensive guide to help developers new to Vulkan, understand all its components fully. To do this I have broken down each section into an example project showcasing how that area of Vulkan is managed in its simplest forum.

## Table of Contents
+ [Building](#Building)
+ [Getting Started](#GettingStarted)



## <a name="Building"></a> Building
Example Coming Soon

## <a name="GettingStarted"></a> Getting Started

### [0 - Instance](0-Instance/)
How to create the underline 'VkInstance' with basic layer validation. 

### [1 - Physical Device](1-PhysicalDevice/)
Find a device on the system that is compatible with our requirements for the system. There could be multiple GPUs within the computer and I show several ways of distinguishing the best choice for the project.

### [2 - Device](2-Device/)
Upon finding the GPU that we want to use, we next create a Vulkan Device instance.

### [3 - Command Pool](3-CommandPools/)
Creating the mechanism that we will use to send messages to the GPU.

### [4 - Buffers](4-Buffers/)
We create a buffer on the GPU, allocate and bind memory to it and show examples of reading and writing to and from it.

### [5 - Descriptors](5-Descriptors/)
Create a descriptor pool and descriptor set that later on will allow for the dynamic binding of resources to a pipeline

### [6 - Swapchain](6-Swapchain/)
Here we create the swapchain and all of its iamges for later rendering steps

### [7 - Renderpass](7-Renderpass/)
Create the render pass, this involves defining what the rendering order will be, how many post processes will there be, how many image attachments will be needed, etc

### [8 - Present](8-Present/)
Render a blank screen with a single color, here we focus on getting the rendering commands created and render a basic screen using them

### [9 - GraphicsPipeline](9-GraphicsPipeline/)
Create a basic graphics pipeline and render a triangle. Here we load a SPIRE-V Vertex and Fragment shader as well as walk through the various settings involved in the creation of a graphics pipeline
