# Procedural Animation

Work in progres...

# About

Procedural animation course.

Inspiration and types:
* Abstract vs regular.
* Nature vs human-made.
* Organic vs hard-surface.

Applications:
* Game worlds (environments, foliage, natural phenomena)
* Animation worlds
* VFX
* Motion graphics
* Generative Art
* Botany and plants
* Visualization
* Arhitecture
* Algorithmic design

The aim:
* Structure of procedural animation
* Theoretical background of procedural animation
* Practical tools and methods for procedural animation
* Conceptual understanding of methods and tools (not low-level implementation)
* Learning by doing
* Presenting using stylized rendering and compositing

# Course 

Procedural animation methods:
* Physically-based approaches
  * classical mechanics, forces and constraints
    * fluids: gases and liquids
    * solids: rigid bodies and soft bodies
* Biological simulation
  * Surface/Volume Growth
  * Surface/Volume Spread modeling
  * Branching (recursion)
    * Trees
    * Roots
  * Reaction, Reaction-diffusion
  * Digital Morphogenesis
  * Phenomenological simulation
* Mathematics:
  * Iterative systems and chaos
  * Cells and automation
* Empirical CG
  * Procedural noise, layering and warping
  * L-Systems
  * Boids 
  * Geometric instancing (including arraying)
  * Particles and force fields

CG methods:
* 3D scene: lights, cameras, materials and shapes (meshes, voxles, curves, etc.)
* Rendering: GPU raster, CPU path-tracing
* Post-processing

Software:
* [Blender](https://www.blender.org/)
* [Houdini](https://www.sidefx.com/)

Literature:
* [STANFORDANIM] D. James: http://graphics.stanford.edu/courses/cs348c/
* [PROCMODEL] Ebert: Texturing and modeling: procedural approach
* [HORIKAWA] J. Horikawa: https://www.youtube.com/watch?app=desktop&v=rj0dEEVU1Ek&ab_channel=Houdini
* https://jhorikawa.gumroad.com/l/GOZFw
* https://natureofcode.com/

### Lecture 1: intro

* Introduction, motivation
* Big picture: procedural modeling, generative art, generative design, algorithmic art, etc.
* Lectures overview

### Lecture: Procedural noise, layering and warping

* Perlin, Worley, flow noise
* Layering noise (fractal sum; fBm)
* Warping noise
* Noise as force fields: particles
* Noise for geometric displacement

### Terrains

* Surface and volume generation
* Noise, heightfields

### Lecture: Geometric instancing

* Procedural modeling of simple shapes 
* Procedural placement of simple shapes (masking, sampling)
* Instace Transformations (rotations, scaling, translation)
* Instace Materials

### Lecture: Particles and force fields

* Particles guided by procedural force fields
  * https://www.artstation.com/artwork/LRwEoA

### Lecture: Branching

* SCA
* L-Systems
* DLA

### Lecture: Growth

* Digital morphogenesis: https://en.wikipedia.org/wiki/Digital_morphogenesis
  * Complex shape development
  * Biology, Geology, Geomorphology and arhitecture
* Eden model
* Iterative procedural algorithms
  * Iterative proportional mesh extrusions

### Lecture: Spread

* Spread over surface or volume points

### Lecture: Physically-based: rigid bodies

* Procedural constraints and forces

### Lecture: Physically-based: soft bodies

* Procedural constraints and forces

### Lecture: Physically-based: liquids

* Procedural constraints and forces

### Lecture: Physically-based: gases

* Procedural constraints and forces