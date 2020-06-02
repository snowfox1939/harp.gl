<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-materials](./harp-materials.md) &gt; [GroundAtmosphereMaterial](./harp-materials.groundatmospherematerial.md) &gt; [updateUniforms](./harp-materials.groundatmospherematerial.updateuniforms.md)

## GroundAtmosphereMaterial.updateUniforms() method

Updates the uniform data of a material used to render an atmosphere.

This includes only uniforms that may change frame by frame, other uniforms are accessed with convenient material setters and getters.

<b>Signature:</b>

```typescript
updateUniforms(shaderMaterial: THREE.ShaderMaterial, object: THREE.Object3D, camera: THREE.Camera, lightDirection: THREE.Vector3): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  shaderMaterial | THREE.ShaderMaterial | Material which uniforms will be updated. |
|  object | THREE.Object3D |  |
|  camera | THREE.Camera | Camera used in rendering. |
|  lightDirection | THREE.Vector3 | The light directional vector in world space. |

<b>Returns:</b>

void
