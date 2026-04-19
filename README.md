# Quiz 8 – Design Research

---

## Part 1: Imaging Technique Inspiration

**Technique: Particle Light Trails**

The imaging technique I've chosen as inspiration is the glowing particle trail effect seen in sci-fi films like *Interstellar* — where streaks of light move across a dark background to convey speed, depth, and atmosphere. What draws me to this technique is how much visual impact it creates from something relatively simple. The effect works by layering many semi-transparent dots along a moving path, each fading out gradually over time to leave a smooth, luminous streak behind. I'd like to bring this into my project because it immediately reads as cinematic and dramatic without needing complex 3D rendering even a basic version would give the work a strong, polished aesthetic that fits the direction I'm going for.

![Star trails over landscape](https://upload.wikimedia.org/wikipedia/commons/0/0c/Star_trails_and_windpump.jpg)

![Light rays through forest](https://upload.wikimedia.org/wikipedia/commons/8/8e/Crepuscular_rays_in_GGP.JPG)

---

## Part 2: Coding Technique Exploration

**Technique: Fading Trail Effect using low-alpha background in p5.js**

The coding technique I've found is a fading trail effect in p5.js, achieved by drawing a semi-transparent black rectangle over the canvas each frame rather than clearing it completely. Because the previous frame isn't fully erased, any moving shape leaves a ghost of itself behind building up into a glowing trail over time. This directly supports the particle trail aesthetic from Part 1. It's also a really approachable technique that doesn't rely on any external libraries, just core p5.js functions, which makes it realistic to implement even as someone just getting started.

![Star trails coding reference](https://upload.wikimedia.org/wikipedia/commons/0/0c/Star_trails_and_windpump.jpg)

[Link to example code](https://editor.p5js.org/codingtrain/sketches/9DnjxCNB-)
