<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-omv-datasource](./harp-omv-datasource.md) &gt; [OmvFeatureFilter](./harp-omv-datasource.omvfeaturefilter.md) &gt; [wantsPolygonFeature](./harp-omv-datasource.omvfeaturefilter.wantspolygonfeature.md)

## OmvFeatureFilter.wantsPolygonFeature() method

Return `false` if the polygon feature should not be processed.

<b>Signature:</b>

```typescript
wantsPolygonFeature(layer: string, geometryType: OmvGeometryType, level: number): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  layer | string | Current layer. |
|  geometryType | [OmvGeometryType](./harp-omv-datasource.omvgeometrytype.md) |  |
|  level | number | Level of tile. |

<b>Returns:</b>

boolean
