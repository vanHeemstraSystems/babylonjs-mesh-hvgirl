# 100 - Introduction

This repository stores the following BabylonJS Meshes

- HVGirl.glb

These resources can be imported in BabylonJS as follows:

```
// Load the mesh asynchronously
SceneLoader.ImportMeshAsync(
  null,
  "https://github.com/vanHeemstraSystems/babylonjs-mesh-hvgirl/raw/main/HVGirl.glb",
  null,
  scene
).then(({ meshes }) => {
  // We now have our mesh loaded into the scene!
  // This is where we could do something with the loaded mesh.

  // ...
});
```
