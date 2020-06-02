<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-materials](./harp-materials.md) &gt; [enableBlending](./harp-materials.enableblending.md)

## enableBlending() function

Enable alpha blending using THREE.CustomBlending setup.

Function enables blending using one of predefined modes, for both color and alpha components: - Src: \[\[THREE.SrcAlphaFactor\]\], Dst: \[\[THREE.OneMinusSrcAlphaFactor\]\] - Src: \[\[THREE.OneFactor\]\], Dst: \[\[THREE.OneMinusSrcAlphaFactor\]\] The second blending equation is used when \[\[THREE.Material.premultipliedAlpha\]\] is enabled for this material.  Blending mode change does not require material update.  THREE.Material.needsUpdate.

<b>Signature:</b>

```typescript
export declare function enableBlending(material: (THREE.Material | THREE.ShaderMaterialParameters) & ForcedBlending): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  material | (THREE.Material \| THREE.ShaderMaterialParameters) &amp; [ForcedBlending](./harp-materials.forcedblending.md) | The material or material parameters to modify. |

<b>Returns:</b>

void
