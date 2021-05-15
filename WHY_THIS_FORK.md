### Why this fork..??

Some personal reasons why I have created this fork..(wip)

I've always wanted to learn raytracing.. since the first time I saw a Pov-Ray 2.0 render.
That scene that was drawn slowly, line by line, on the screen of an old 386 sx,
until completing a image of a checkered plane, on which rested a red, brilliant and perfect sphere.
Thus, this project is only an excuse to continue learning in the best possible way: practicing.

### Why an integration in Blender..??

On the other hand, Blender is a magnificent Open Source project that allows people without an academic training,
learn about complex software application development.
The purpose of this integration is to facilitate the creation of scenes, the definition of materials and render them easily.
Although there is no defined roadmap, this is a list of the things that I would like to implement and their current state.

#### Geomety:

The geometry is exported in the compact and efficient binary PLY format.

- [x] Meshes.
- [x] Extruded Curves
- [x] MetaBalls ( as polygon mesh..)
- [x] Instances
- [x] Proxys ( as instances..)
- [x] Hair ( as instantiated object)
- [ ] Native hair(wip)
- [ ] Point Clouds

#### Materials:

Almost all PBRT materials are currently supported, although some use the default values.

Translate and implementing the materials using nodes is not a easy task.

#### Textures:

- [x] Bitmap
- [ ] Procedural textures



