---
name: SandScape
tools: [Unity, C#, Blender]
image: https://PuppyGummy.github.io/picx-images-hosting/QQ20240618-233524@2x.54xmarwl39.webp
description: A digital solution for sand tray therapy
---

# SandScape

<p style="color:DarkGrey">
A client project for Digital Lab, BC Children's Hospital
</p>

{% capture carousel_images %}
https://PuppyGummy.github.io/picx-images-hosting/QQ20240618-233600@2x.6ik5et7n3w.webp
https://PuppyGummy.github.io/picx-images-hosting/QQ20240618-233613@2x.26lc79obli.webp
https://PuppyGummy.github.io/picx-images-hosting/QQ20240618-233628@2x.1sewgeg0q9.webp
https://PuppyGummy.github.io/picx-images-hosting/QQ20240618-233840@2x.58h88hpnse.webp
https://PuppyGummy.github.io/picx-images-hosting/be818a7a-a832-437a-9fe7-33552ebabf73.7sn2l4pmef.webp
{% endcapture %}
{% include elements/carousel.html %}

{% include elements/button.html link="https://projects.thecdm.ca/sandscape/" text="Play Demo" block=true %}

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
Description
</h3>
<br>

SandScape initiative focuses on delivering an engaging, virtual sand tray therapy platform explicitly designed for children and teenagers in Vancouver who have experienced trauma and find traditional therapy challenging in collaboration with BC Children's Hospital Digital Lab. The project aims to provide a safe and interactive space for children to express themselves and explore their emotions through the use of a virtual sand tray. 
<br>

{% include elements/video.html id="JJVP5A7261s" %}

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center">
About
</h3>
<br>

This is a 12-week client project for my masters program. In this project, I was collaborating with another developer on the implementation of features. 

In this project, we drew inspiration from [Simply Sand Play](https://simplysandplay.com/) but enhanced the user experience, particularly with the dragging interactions. Unlike Simply Sand Play, where dragging is laggy, we implemented smooth dragging and improved precision by integrating a runtime gizmo tool. We also introduced an innovative customization system, allowing children to express their creativity more freely while telling their stories. Additionally, I proposed a feature to disable the physics (mainly collisions) of the miniatures, enabling users to combine multiple miniatures and create unique, custom figures.

Compared to my other projects, this was a larger-scale endeavor, and it became a valuable experience in teamwork and collaboration. I gained significant insights into version control using Git and learned how to effectively manage a project with multiple developers, ensuring smooth coordination and integration of our work.

#### Challenges & Solutions

One of the challenges in this project was implementing a robust undo/redo feature. This required not only tracking the transformations (position, rotation, and scale) of miniatures but also handling complex operations like adding/removing objects and customizing elements such as changing colors or outfits. To achieve this, I designed a custom data structure to record user actions and utilized two stacks: one for undo operations and one for redo operations. Each operation, whether it involved modifying the transform, adding or deleting objects, or applying customizations, was stored as an individual record in these stacks. For operations involving model addition/removal, I dynamically loaded and instantiated the relevant prefab files using Unity’s Resources.Load function to ensure that the correct assets were managed and restored seamlessly during undo/redo actions.

This project demonstrated my ability to work effectively within a team and collaborate on a more complex and demanding initiative, strengthening my teamwork and communication skills. It also showcased my problem-solving skills, particularly in designing and implementing complex features like the undo/redo system.

#### Contributions

I was mainly responsible for the following tasks:
- Implemented interaction with miniatures, either single or multiple at a time, which includes:
  - selection (click and box selection)
  - dragging
  - scaling (with mouse wheel/UI button)
  - rotating
  - burying (like in the real sand tray therapy)
  - locking/unlocking
  - duplicating
  - removing

- Tracked user actions with stacks to enable undo and redo functionality.

- Serialized data into JSON format with custom data structures for local saving and loading.

<p class="text-center" style="color:DarkGrey">
---
</p>

<br>
<div class="text-center">
<a style="color:DarkGrey" href="https://github.com/PuppyGummy/SandScape">
view source code here
</a>
</div>