---
name: Procedural Walking Animation
tools: [Unity, C#, Animation Rigging, Procedural Animation]
image: https://PuppyGummy.github.io/picx-images-hosting/QQ20241202-165318.3d4u24fd68.webp
description: A code-driven walking animation system that generates realistic animations in real-time
---

# Procedural Walking Animation

<p style="color:DarkGrey">
A personal project
</p>

{% include elements/video.html id="UxGvjkSX1CI" %}

{% include elements/button.html link="https://github.com/PuppyGummy/ProceduralWalkingAnimation" text="Source Code" block=true %}

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
Description
</h3>
<br>

This project implements procedural walking animation in Unity using the Animation Rigging package. The system uses inverse kinematics (IK) to drive the leg movements, generating realistic animations in real-time.

<br>

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center">
About
</h3>
<br>

##### Challenges & Solutions

The main challenge in this project was the lack of resources on procedural animation. I explored numerous tutorials, but most were either outdated or not suitable for my project. Ultimately, I referred to Unity's official tutorials, analyzed the related source code, and made targeted modifications to adapt a two-legged system into one suitable for six legs. Additionally, I needed to adjust the character's rotation to align with the ground's normal. To address this, I found a tutorial by a French creator on YouTube, translated his video, and learned his approach to solve the problem.

This experience demonstrated my ability to independently research and adapt to challenges when resources are scarce. I showcased problem-solving skills by analyzing and modifying existing systems to fit unique project requirements, as well as resourcefulness in finding and learning from alternative solutions, even overcoming language barriers to acquire the knowledge I needed.

##### Contributions

In this project, I:
- Set up IK solvers to drive the leg movements based on the target positions using raycasting.
- Aligned the character with the ground normal using an arc raycast.
- Implemented scanning of the environment to ensure a smooth transition between different terrains.


<p class="text-center" style="color:DarkGrey">
---
</p>
