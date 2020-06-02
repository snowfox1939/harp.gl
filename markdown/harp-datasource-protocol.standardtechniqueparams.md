<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [StandardTechniqueParams](./harp-datasource-protocol.standardtechniqueparams.md)

## StandardTechniqueParams interface

Standard technique parameters.

<b>Signature:</b>

```typescript
export interface StandardTechniqueParams extends BaseTechniqueParams 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [alphaMap](./harp-datasource-protocol.standardtechniqueparams.alphamap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as alpha map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.alphaMap |
|  [alphaMapProperties](./harp-datasource-protocol.standardtechniqueparams.alphamapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [alphaTest](./harp-datasource-protocol.standardtechniqueparams.alphatest.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | The material will not be rendered if the opacity is lower than this value. See https://threejs.org/docs/\#api/en/materials/Material.alphaTest. |
|  [bumpMap](./harp-datasource-protocol.standardtechniqueparams.bumpmap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as bump map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.bumpMap |
|  [bumpMapProperties](./harp-datasource-protocol.standardtechniqueparams.bumpmapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [color](./harp-datasource-protocol.standardtechniqueparams.color.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;[StyleColor](./harp-datasource-protocol.stylecolor.md)<!-- -->&gt; | Color of the feature in hexadecimal or CSS-style notation, for example: <code>&quot;#e4e9ec&quot;</code>, <code>&quot;#fff&quot;</code>, <code>&quot;rgb(255, 0, 0)&quot;</code>, or <code>&quot;hsl(35, 11%, 88%)&quot;</code>. See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.color.  color-hex |
|  [depthTest](./harp-datasource-protocol.standardtechniqueparams.depthtest.md) | boolean | Skip rendering clobbered pixels. See https://threejs.org/docs/\#api/en/materials/Material.depthTest. |
|  [displacementMap](./harp-datasource-protocol.standardtechniqueparams.displacementmap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as displacement map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.displacementMap |
|  [displacementMapProperties](./harp-datasource-protocol.standardtechniqueparams.displacementmapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [emissive](./harp-datasource-protocol.standardtechniqueparams.emissive.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;[StyleColor](./harp-datasource-protocol.stylecolor.md)<!-- -->&gt; | Emissive (light) color of the material, essentially a solid color unaffected by other lighting. Default is black. See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.emissive.  color-hex |
|  [emissiveIntensity](./harp-datasource-protocol.standardtechniqueparams.emissiveintensity.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | Intensity of the emissive light. Modulates the emissive color. Default is <code>1</code>. See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.emissiveIntensity. |
|  [emissiveMap](./harp-datasource-protocol.standardtechniqueparams.emissivemap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as emissive map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.emissiveMap |
|  [emissiveMapProperties](./harp-datasource-protocol.standardtechniqueparams.emissivemapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [map](./harp-datasource-protocol.standardtechniqueparams.map.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) |  |
|  [mapProperties](./harp-datasource-protocol.standardtechniqueparams.mapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [metalness](./harp-datasource-protocol.standardtechniqueparams.metalness.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | How much the material is like a metal. Nonmetallic materials such as wood or stone use <code>0.0</code>, metallic ones use <code>1.0</code>, with nothing (usually) in between. Default is <code>0.0</code>. A value between <code>0.0</code> and <code>1.0</code> can be used for a rusty metal look. If <code>metalnessMap</code> is also provided, both values are multiplied. See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.metalness. |
|  [metalnessMap](./harp-datasource-protocol.standardtechniqueparams.metalnessmap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as metalness map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.metalnessMap |
|  [metalnessMapProperties](./harp-datasource-protocol.standardtechniqueparams.metalnessmapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [normalMap](./harp-datasource-protocol.standardtechniqueparams.normalmap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as normal map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.normalMap |
|  [normalMapProperties](./harp-datasource-protocol.standardtechniqueparams.normalmapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [normalMapType](./harp-datasource-protocol.standardtechniqueparams.normalmaptype.md) | number |  |
|  [opacity](./harp-datasource-protocol.standardtechniqueparams.opacity.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | For transparent lines, set a value between 0.0 for totally transparent, to 1.0 for totally opaque. See https://threejs.org/docs/\#api/en/materials/Material.opacity. |
|  [refractionRatio](./harp-datasource-protocol.standardtechniqueparams.refractionratio.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | The index of refraction (IOR) of air (approximately 1) divided by the index of refraction of the material. It is used with environment mapping modes <code>THREE.CubeRefractionMapping</code> and <code>THREE.EquirectangularRefractionMapping</code>. The refraction ratio should not exceed <code>1</code>. Default is <code>0.98</code>. See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.refractionRatio. |
|  [roughness](./harp-datasource-protocol.standardtechniqueparams.roughness.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | How rough the material appears. <code>0.0</code> means a smooth mirror reflection. <code>1.0</code> means fully diffuse. Default is <code>1.0</code>. See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.roughness. |
|  [roughnessMap](./harp-datasource-protocol.standardtechniqueparams.roughnessmap.md) | string \| [TextureBuffer](./harp-datasource-protocol.texturebuffer.md) | URL or texture buffer that should be used as roughness map. See: https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.roughnessMap |
|  [roughnessMapProperties](./harp-datasource-protocol.standardtechniqueparams.roughnessmapproperties.md) | [TextureProperties](./harp-datasource-protocol.textureproperties.md) |  |
|  [textureCoordinateType](./harp-datasource-protocol.standardtechniqueparams.texturecoordinatetype.md) | [TextureCoordinateType](./harp-datasource-protocol.texturecoordinatetype.md) | Whether and how texture coordinates should be generated. No texture coordinates are generated if <code>undefined</code>. Should be set if any texture assigned (e.g. <code>map</code>, <code>normalMap</code>, ...). |
|  [transparent](./harp-datasource-protocol.standardtechniqueparams.transparent.md) | boolean | Set to 'true' if line should appear transparent. Rendering transparent lines may come with a slight performance impact. See https://threejs.org/docs/\#api/en/materials/Material.transparent. |
|  [vertexColors](./harp-datasource-protocol.standardtechniqueparams.vertexcolors.md) | boolean | If <code>vertexColors</code> is <code>true</code>, every vertex has color information, which is interpolated between vertices. See https://threejs.org/docs/\#api/en/materials/Material.vertexColors. |
|  [wireframe](./harp-datasource-protocol.standardtechniqueparams.wireframe.md) | boolean | A value of <code>true</code> creates a wireframe geometry. (May not be supported with all techniques). See https://threejs.org/docs/\#api/en/materials/MeshStandardMaterial.wireframe. |
