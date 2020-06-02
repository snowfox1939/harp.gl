<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-omv-datasource](./harp-omv-datasource.md) &gt; [OmvFeatureFilter](./harp-omv-datasource.omvfeaturefilter.md)

## OmvFeatureFilter interface

The `OmvFeatureFilter` is designed to work in an `OmvVisitor`<!-- -->/`visitOmv` combination (for example, `OmvDecoder`<!-- -->). Returning `false` from any of the calls terminates processing of that layer or feature.

The `OmvFeatureFilter` is an "early-opt-out" filter, which cannot filter individual features, because at that point the features are not really decoded. Use the \[\[OmvFeatureModifier\]\] to filter for individual features.

<b>Signature:</b>

```typescript
export interface OmvFeatureFilter 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [hasKindFilter](./harp-omv-datasource.omvfeaturefilter.haskindfilter.md) | boolean | Returns <code>true</code> if the filter contains rules for specific kinds. |

## Methods

|  Method | Description |
|  --- | --- |
|  [wantsKind(kind)](./harp-omv-datasource.omvfeaturefilter.wantskind.md) | Return <code>false</code> if kind of object is not enabled and the geometry should not be created. |
|  [wantsLayer(layer, level)](./harp-omv-datasource.omvfeaturefilter.wantslayer.md) | Return <code>false</code> if the layer should not be processed. |
|  [wantsLineFeature(layer, geometryType, level)](./harp-omv-datasource.omvfeaturefilter.wantslinefeature.md) | Return <code>false</code> if the line feature should not be processed. |
|  [wantsPointFeature(layer, geometryType, level)](./harp-omv-datasource.omvfeaturefilter.wantspointfeature.md) | Return <code>false</code> if the point feature should not be processed. |
|  [wantsPolygonFeature(layer, geometryType, level)](./harp-omv-datasource.omvfeaturefilter.wantspolygonfeature.md) | Return <code>false</code> if the polygon feature should not be processed. |
