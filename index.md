# Introduction
This is a project for UCSD's Rendering class. It is an implementation of 
a ray tracer which handles Ashikhmin BRDF materials and motion blur.

# Animated GIF
This is a 4x4 sampling rate GIF of bouncing dragons.

![DRAGONS](https://raw.githubusercontent.com/rnlee0054/MotionBlurRayTracer/master/Images/cse168_dragon1.gif)

# Test images
All test images below are 4x4.

Below, we show that glm::interpolate can interpolate correctly for rotations, not only translations.

![DRAGONS](https://raw.githubusercontent.com/rnlee0054/MotionBlurRayTracer/master/Images/rota.png)

This is the first translation of the animation, with the least movement.

![DRAGONS](https://raw.githubusercontent.com/rnlee0054/MotionBlurRayTracer/master/Images/1.png)

This is the translation frame with the greatest movement.

![DRAGONS](https://raw.githubusercontent.com/rnlee0054/MotionBlurRayTracer/master/Images/3.png)

