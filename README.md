# Quiz 8 – Design Research

---

## Part 1: Imaging Technique Inspiration

**Technique: Particle Light Trails**

The imaging technique I've chosen is the glowing particle trail effect — something I've always noticed in sci-fi films I love like *Interstellar*, where streaks of light cutting across a dark background create this really intense, cinematic mood. That dramatic atmosphere is exactly what draws me to it. The effect builds up by layering semi-transparent shapes along a moving path, each one fading out over time to create a smooth, luminous streak. I want to bring that same feeling into my project — that sense that something visually heavy and dramatic is happening, even if the underlying code is actually pretty simple to pull off.

![Star trails over landscape](https://upload.wikimedia.org/wikipedia/commons/0/0c/Star_trails_and_windpump.jpg)

![Light rays through forest](https://upload.wikimedia.org/wikipedia/commons/8/8e/Crepuscular_rays_in_GGP.JPG)

---

## Part 2: Coding Technique Exploration

**Technique: Fading Trail Effect using low-alpha background in p5.js**

The technique I found works by drawing a semi-transparent black rectangle over the canvas every frame instead of fully clearing it. That means whatever was on screen before doesn't disappear completely — it just fades a little, so any moving shape naturally leaves a trail behind it. Over time, those trails stack up and glow, which is exactly the dramatic visual mood I'm going for from Part 1. What I like about it is that it's built entirely from basic p5.js functions with no extra libraries needed, so it's something I can actually see myself working with, even as someone brand new to this.

![Fading trail effect](https://upload.wikimedia.org/wikipedia/commons/8/8e/Crepuscular_rays_in_GGP.JPG)

[Link to example code](https://editor.p5js.org/codingtrain/sketches/9DnjxCNB-)
