# VulkanTutorial-Android

Step by step tutorial of Vulkan on Android, follow https://vulkan-tutorial.com.

+ We need [`vulkan_wrapper`](https://developer.android.com/ndk/guides/graphics/getting-started.html#using) on Android, which could be [download from GitHub](https://github.com/LunarG/VulkanSamples/tree/master/common).
+ In Android Studio, just put shader code under `src/main/shaders` folder, they will be compiled into `.spv` files, and packaged as assets.

## Conan package manager

Conan support is setup according to [this tutorial](https://docs.conan.io/en/latest/integrations/android_studio.html), to install conan, run `pip install conan`.
