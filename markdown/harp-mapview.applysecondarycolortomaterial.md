<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [applySecondaryColorToMaterial](./harp-mapview.applysecondarycolortomaterial.md)

## applySecondaryColorToMaterial() function

Apply technique color to material taking special care with transparent (RGBA) colors.

 This function is intended to be used with secondary, triary etc. technique colors, not the base ones that may contain transparency information. Such colors should be processed with \[\[applyTechniqueBaseColorToMaterial\]\] function.

<b>Signature:</b>

```typescript
export declare function applySecondaryColorToMaterial(materialColor: THREE.Color, techniqueColor: Value | Expr, env?: Env): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  materialColor | THREE.Color |  |
|  techniqueColor | [Value](./harp-datasource-protocol.value.md) \| [Expr](./harp-datasource-protocol.expr.md) |  |
|  env | [Env](./harp-datasource-protocol.env.md) | \[\[Env\]\] instance used to evaluate \[\[Expr\]\] based properties of \[\[Technique\]\] |

<b>Returns:</b>

void
