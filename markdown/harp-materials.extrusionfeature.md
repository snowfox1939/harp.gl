<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-materials](./harp-materials.md) &gt; [ExtrusionFeature](./harp-materials.extrusionfeature.md)

## ExtrusionFeature namespace

<b>Signature:</b>

```typescript
export declare namespace ExtrusionFeature 
```

## Functions

|  Function | Description |
|  --- | --- |
|  [isEnabled(extrusionMaterial)](./harp-materials.extrusionfeature.isenabled.md) | Checks if feature is enabled based on \[\[ExtrusionFeature\]\] properties. |
|  [onBeforeCompile(extrusionMaterial, shader)](./harp-materials.extrusionfeature.onbeforecompile.md) | This function should be called on implementors of ExtrusionFeature in the <code>onBeforeCompile</code> callback of that material. It adds the required code to the shaders and declares the new uniforms that control extrusion. |
|  [patchGlobalShaderChunks()](./harp-materials.extrusionfeature.patchglobalshaderchunks.md) | Patch the THREE.ShaderChunk on first call with some extra shader chunks. |
|  [updateExtrusionFeature(extrusionMaterial)](./harp-materials.extrusionfeature.updateextrusionfeature.md) | Update the internals of the <code>ExtrusionFeature</code> depending on the value of \[\[extrusionRatio\]\]. |
