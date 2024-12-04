---
name: Weibo Lucky Draw Tool
tools: [Python, HTML, Flask, Weibo API, Cloud Service]
image: https://PuppyGummy.github.io/picx-images-hosting/LuckyDraw_cover.6bh45nd9km.webp
description: A tool for drawing users from Weibo posts
---

# Weibo Lucky Draw Tool

<p style="color:DarkGrey">
A personal web project
</p>

{% capture carousel_images %}
https://PuppyGummy.github.io/picx-images-hosting/QQ20241203-185257.6bh476blmn.webp
{% endcapture %}
{% include elements/carousel.html %}

<div class="d-flex w-100 gap-2">
  <!-- Button 1: View Demo -->
  <a class="m-1 btn btn-primary flex-grow-1" href="https://luckydrawtool.online">
    View App
  </a>

  <!-- Button 2: Code -->
  <a class="m-1 btn btn-secondary flex-grow-1" href="https://github.com/PuppyGummy/WeiboLuckyDrawTool">
    Source Code
  </a>
</div>

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
Description
</h3>
<br>

This is an online tool for drawing users from Weibo posts. It is designed to help Weibo users randomly select users from their followers who have liked or reposted their posts.

<br>

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center">
About
</h3>
<br>

##### Challenges & Solutions

Driven by my interest in building this tool and its potential to help other Weibo users, I decided to challenge myself. Without any prior experience in developing web apps, the biggest obstacle was figuring out how to get started. I had to rely entirely on self-learning to complete this project. While the backend was relatively straightforward, I struggled to connect it with the frontend. By seeking guidance from ChatGPT, I learned how to use Flask to enable communication between the two.  

To make the tool publicly accessible, I needed to deploy it to a server, which required configuring the server environment and installing project dependencies. Once that was resolved, a new challenge arose: the callback URL for Weibo's OAuth 2.0 authorization needed to use the HTTPS protocol. This meant configuring an SSL certificate for my server. I encountered repeated failures—neither tutorials nor assistance from LLMs provided a solution. Eventually, I consulted experienced developers online and learned that the issue stemmed from regional policies tied to my domain registration. Understanding these policies allowed me to overcome the problem, successfully deploy the tool, and release it after testing with the help of friends.

This experience demonstrated my resilience and adaptability in overcoming unfamiliar challenges. It highlighted my ability to independently learn new skills, such as web app development and server deployment, and to persist through repeated failures. It also showcased my resourcefulness in seeking help from various sources—whether it was consulting AI tools, researching policies, or reaching out to experienced developers—to find practical solutions and achieve my goals.

##### Contributions

This is a personal project. In this project, I:
- Developed a backend service using Python and Flask to interact with the Weibo API and perform the lucky draw.
  - Authorized the application to access the Weibo API using OAuth 2.0.
  - Redirected users to the callback URL after authorization to obtain the access token.
  - Used the access token to fetch the list of users who liked or reposted the Weibo post.
  - Implemented pagination query to fetch all users.
- Created a frontend interface using HTML and CSS to allow users to input the Weibo post URL and draw users.
- Deployed the tool on a cloud service to make it accessible online.
- Configured the SSL certificate to ensure secure communication between the client and the server.

<p class="text-center" style="color:DarkGrey">
---
</p>