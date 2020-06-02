<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [getMaterialConstructor](./harp-mapview.getmaterialconstructor.md)

## getMaterialConstructor() function

Returns a \[\[MaterialConstructor\]\] basing on provided technique object.

<b>Signature:</b>

```typescript
export declare function getMaterialConstructor(technique: Technique, shadowsEnabled: boolean): MaterialConstructor | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  technique | [Technique](./harp-datasource-protocol.technique.md) | \[\[Technique\]\] object which the material will be based on. |
|  shadowsEnabled | boolean | Whether the material can accept shadows, this is required for some techniques to decide which material to create. |

<b>Returns:</b>

[MaterialConstructor](./harp-mapview.materialconstructor.md) \| undefined
