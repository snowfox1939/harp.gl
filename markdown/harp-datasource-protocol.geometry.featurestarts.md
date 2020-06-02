<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [Geometry](./harp-datasource-protocol.geometry.md) &gt; [featureStarts](./harp-datasource-protocol.geometry.featurestarts.md)

## Geometry.featureStarts property

Optional sorted list of feature start indices. The indices point into the index attribute. Feature i starts at featureStarts\[i\] and ends at featureStarts\[i+1\]-1, except for the last feature, which ends at index\[index.length-1\].

<b>Signature:</b>

```typescript
featureStarts?: number[];
```