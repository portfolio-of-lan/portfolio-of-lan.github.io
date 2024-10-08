---
name: Unstable Concoction
tools: [Unity, C#, Aseprite]
image: https://PuppyGummy.github.io/picx-images-hosting/title1.8dwq7g0zjv.webp
description: A puzzle game made in a gamejam
---

# Unstable Concoction

<p style="color:DarkGrey">
a simple puzzle game
</p>

{% capture carousel_images %}
https://PuppyGummy.github.io/picx-images-hosting/intro.58h88i6kmm.webp
https://PuppyGummy.github.io/picx-images-hosting/intro2.51e0d2kf74.webp
https://PuppyGummy.github.io/picx-images-hosting/level2.4uashmy9ro.webp
https://PuppyGummy.github.io/picx-images-hosting/level3.39l1i612bb.webp
{% endcapture %}
{% include elements/carousel.html %}

<!-- {% include elements/button.html link="https://chocolate-kami.itch.io/unstableconcoction" text="Play Game" block=true %} -->

<div class="d-flex w-100 gap-2">
  <!-- Button 1: Play Demo -->
  <a class="m-1 btn btn-primary flex-grow-1" href="https://chocolate-kami.itch.io/unstableconcoction">
    Play Game
  </a>

  <!-- Button 2: Download -->
  <a class="m-1 btn btn-secondary flex-grow-1" href="https://github.com/PuppyGummy/UnstableConcoctionProject">
    Source Code
  </a>
</div>

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center">
About
</h3>

<br>
It’s a puzzle game made within 72 hours by me and another classmate of mine, during Ludum Dare 49, a game jam. I participated in designing the game background and mechanism and illustrated all the image resources in the form of pixel art, such as the title, the animation of the character, the look of different elements and ground blocks, the ending, etc.

Also, I made all the scenes with Unity engine, including the title scene, the introduction scene, the level selection scene, and the ending scene. I was in charge of how the user interface should interact with players and what effect it should have. In addition, I implemented the dialogue with an open-source plug-in called Yarn Spinner. Finally, I designed several puzzles on my own as well. ( Level 2 and level 3 were designed by me. )

It was my first game jam, so the biggest challenge was time limitation. I had to make a lot of compromises, such as the number of levels, the quality of the puzzles, etc. However, it was also my first complete game, and I learned the whole process of making a game, including testing and publishing, which was really fun.
<br>

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
Background
</h3>
<br>

There are six elements in the world:

+ the <font color=DeepSkyBlue>Arcane</font>

+ the <font color=FireBrick>Blight</font>

+ the <font color=DeepPink>Crystal</font>

+ the <font color=DarkMagenta>Diffusal</font>

+ the <font color=Gold>Essence</font>

+ the <font color=DarkSeaGreen>Force</font>

The magical reactions among them create this beautiful world.

... And you, are a bottle of potion,

who wants to become the greatest alchemist of the world!

In order to do so, you shall find the hidden magic circle.

But watch out for every step you make, since the chemical you carry may easily get spilled.

And then, BOOM! The reaction with the ground might kill you.

Also, you may collect elements on the way, and mix it with the chemical inside you to form a new component.

You could use the potion you carry to corrupt the door that gets in your way.

Do keep in mind that some chemicals are inert and would not react with others.

By the way, the reaction with the door could also form a new element and thus changing your chemical.

Use your wisdom to solve the puzzles!

<p class="text-center" style="color:DarkGrey">
---
</p>

<h3 class="text-center"> 
How to Play
</h3>
<br>
 
You can <font color=DodgerBlue><b><i>click</i></b></font> the ground to move the character. <font color=DodgerBlue><b><i>If the destination is not reachable, the movement will be forbidden.</i></b></font>

You can collect elements in the scenes. If the given element can't react with the concoction in your bottle, nothing will happen, or you will get a new concoction. You can judge the type of elements and concoctions by the <font color=DodgerBlue><b><i>colour.</i></b></font>

Concoctions in the bottle will be <font color=DodgerBlue><b><i>spilt</i></b></font> after every movement. The ground blocks may be eroded if they can react. Be careful that you can't move to a null block.

You need to break doors using some specified concoctions, or you can't pass them. When you get the <font color=DodgerBlue><b><i>Magic Circle</i></b></font>, you could get to the next level. 

Don't be afraid of trying! 

+ If you make a wrong decision, you can press <font color=Crimson><b><i>Z</i></b></font> to undo it. 
+ You can also press <font color=Crimson><b><i>R</i></b></font> to restart the whole game. 
+ If you want to get back to the level selection menu, just press <font color=Crimson><b><i>ESC</i></b></font>. 

Good luck and thanks for your playing!

![](https://PuppyGummy.github.io/picx-images-hosting/character-final.2a4y4zyb57.webp)

<p class="text-center" style="color:DarkGrey">
---
</p>

The reaction table is as follows:

+ Arcane + Diffusal = Crystal

+ Arcane + Force = Essence

+ Blight + Crystal = Essence

+ Blight + Force = Crystal

+ Crystal + Essence = Force

+ Crystal + Force = Arcane

+ Diffusal + Essence = Crystal

+ Diffusal + Force = Blight

If you get stuck in the game, you could check the table above.

<p class="text-center" style="color:DarkGrey">
---
</p>