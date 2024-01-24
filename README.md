# Advanced-Graphics-Assignments

## Assignment 1
**Assignment description:**
Draw a house using canvas and javascript. You are able to make the house as fancy or as complicated as you want, but you have to add the following features:

1. The house should be drawn in a HTML canvas
2. The house should not use any images
3. The house should have a front wall
4. The house should have a roof
5. The house should have at least a door
6. The house should have at least a window

## Assignment 2

This homework consists of a few small exercises related to shaders, they are meant as a warm-up for the larger individual project. It is highly recommended that you do them before starting on the individual project.


**Assignment description:**
1. Make a shader where the image intensity decreases exponentially from the center. The center should be of colour vec4(1.0, 0.0, 0.0, 1.0), while the points at the circumference that touches the sides should be roughly of colour vec4(vec3(0.0),1.0). You can model this roughly with e<sup>−√x<sup>2</sup>+y<sup>2</sup>.</sup> Hint: Use length(), mix(), and exp().
2. Draw a box in the center of the canvas using a fragment shader. It should be half as wide and half as tall as the canvas and in the center. Next, have the vertex shader move the box off center and spin it around. Make sure the box is mainly on the canvas and that the animation is neither too fast nor too slow. Hint: use mat3 to create 2D homogeneous matrices and transform the vertices.
3. Create the letter A using Signed Distance Functions. You are free to use any font as a reference as long as the letter is readable. Hint: use https://iquilezles.org/www/articles/distfunctions2d/distfunctions2d.htm for definitions of the different primitives there are in 2D.

## Assignment 3

This homework consists of creating a simple scene in 3D.

**Assignment description:**
Create a simple scene with [Neon Genesis Evangelion’s Ramiel](https://duckduckgo.com/?q=evangelion+ramiel&iax=images&ia=images). The scene should have the following:

1. A floor which can be grey or brown.
2. An octohedron (Ramiel) that should be blue.
3. Background should be white or light blue that is not confused with Ramiel

The scene should:
1. Be defined using polygon meshes
2. The meshes should be gl.TRIANGLE_STRIP
3. Use transformations to position Ramiel
4. Instead of lighting, define colour based on depth (z coordinate relative to camera, with darker colours the further away)
5. Make the octohedron spin around slowly
6. Use a perspective camera
7. Make sure Ramiel is completely inside the rendered scene

## Assignment 4

**Assignment description:**
Shade the provided simple scene with three types of illumination: ambient, directional, and either a point or spot light. All the illumination should be done at the same time. The template is colour coding the normals, please use a solid colour instead (constant albedo).

## Individual Project

**Assignment description:**
In this project, you will be making a fragment shader based on a topic. You will have to design a generative design function in the shader to procedurally generate a design, without using any textures.

**Topic**
This years topic is Sea Slugs! A diversity of marine gastropod moluscs or sea snails that either do not have shells or do not appear to have shells are known as sea slugs, with the most common family being that of nudibrachs. In general, they are small and have high toxicity. One of the cutest ones is the Costasiella kuroshimae known as “Sea Sheep” which are kleptoplastic, which means they eat algae and then store the chloroplasts to continue performing photosynthesis.

[Selected Student Works](https://esslab.jp/~ess/en/teaching/2023/acg/individual/)