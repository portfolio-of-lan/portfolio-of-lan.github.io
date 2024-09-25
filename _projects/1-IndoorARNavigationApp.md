---
name: Indoor AR Navigation App
tools: [Unity, C#, AR Foundation, ARCore, ARKit]
image: https://PuppyGummy.github.io/picx-images-hosting/QQ20240915-235402.92q3alsbpd.webp
description: A mobile application that helps users navigate indoors using AR technology
---

# Indoor AR Navigation App

<p style="color:DarkGrey">
A client project for Digital Lab, BC Children's Hospital
</p>

{% capture carousel_images %}
https://PuppyGummy.github.io/picx-images-hosting/image-(2).2a51o5b6qk.webp
https://PuppyGummy.github.io/picx-images-hosting/IMG_3878.8ad7svg3ix.webp
{% endcapture %}
{% include elements/carousel.html %}

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
Description
</h3>
<br>

BC Children's Hospital is facing navigation challenges due to their large and complex campus, leading to confusion, appointment delays, and clinic disruptions. This project aimed to resolve this by developing an augmented reality (AR) navigation app using ARKit and advanced navigation technologies. The app overlays real-time directional cues onto users' mobile devices, allowing them to easily find specific departments and services. The solution enables the hospital to manage and modify navigation routes, enhancing the overall experience for patients, visitors, and staff. The scope also includes a points of interest (POI) feature, with AR content floating above specific locations, providing additional information and enhancing the user experience.

<br>

{% include elements/video.html id="nNelwdF1W-I" %}

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center">
About
</h3>
<br>

This is a 12-week client project in cooperation with Digital Lab, BC Children's Hospital. 

##### Challenges

The biggest hurdle in implementing indoor navigation was how to locate the users(user localization). Typically, there are three common methods: external hardware (like beacons), visual positioning systems (VPS) using machine learning, and visual markers. I initially planned to use VPS and spent several days researching, only to find that most of the resources online were deprecated, and we didn’t have time to build the system from scratch. Beacons were not a viable option either due to long shipping times and a limited budget (200 CAD for the entire project). This left me with one option: visual markers.

However, visual markers couldn’t provide us with a smooth experience, as users need to scan them very frequently to locate themselves. Then, just four weeks before the deadline, the client shifted priorities, asking me to focus on the points of interest(POI) feature, a whole new system that they might not have realized. That is to say, I had to build a system for placing, editing, customizing, saving, and sharing ARAnchors within just four weeks, despite having no prior experience with ARAnchors.

##### Solutions

To improve the user experience, I recommended that our client, Digital Lab, explore beacons or third-party services after taking over the project. I researched several vendors and had meetings with some of them, and developed an evaluation metric to weigh their advantages. The research was documented and provided to the client as part of the deliverables.

As the lead developer, I tried my best to deliver the POI system. One significant challenge was saving and restoring ARAnchors. Saving and restoring the anchors was tricky since each anchor is assigned a few feature points of its surroundings to bind the anchor with the corresponding physical space and avoid drifting. Simply saving the anchor’s pose won’t work, because the feature points are missing. In the end, I used ARKit to save the whole ARWorldMap. With the anchors saved locally, I then faced the task of sharing the data across devices to ensure a consistent experience. By that time, I had only two days left for final delivery, and I started learning Firebase. Not only did I have to upload the ARWorldMap data, but also any associated media. I utilized every resource available, from developer documentation to YouTube tutorials and AI tools, and successfully implemented cloud sharing just in time.

I believe this project demonstrated my ability to communicate and collaborate effectively with clients and stakeholders, particularly in a professional setting. It also highlighted my proactive problem-solving, strategic thinking, and decision-making skills, as I evaluated multiple solutions and proposed the most viable option, ensuring the client was fully informed. Also worth noting is my ability to quickly adapt, learn new technologies, and deliver complex solutions under tight deadlines.

##### Contributions

In this project, I have accomplished the following tasks:
- Implemented indoor navigation using pre-built building models and NavMesh, utilizing visual markers for positioning.
- Developed customizable AR content (text, images, videos) using ARAnchor, enabling placement, deletion, and editing of transform, to serve as points of interest.
- Implemented local saving and loading of ARAnchor using ARKit's ARWorldMap.
- Enabled cross-device AR content sharing via Firebase for a consistent user experience.


<p class="text-center" style="color:DarkGrey">
---
</p>

<br>
<div class="text-center">
<a style="color:DarkGrey" href="https://github.com/PuppyGummy/ARNavi">
view source code here
</a>
</div>