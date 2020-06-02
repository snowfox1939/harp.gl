<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapViewUtils](./harp-mapview.mapviewutils.md) &gt; [estimateObject3dSize](./harp-mapview.mapviewutils.estimateobject3dsize.md)

## MapViewUtils.estimateObject3dSize() function

Computes estimate for size of a THREE.Object3D object and its children. Shared materials and/or attributes will be counted multiple times.

<b>Signature:</b>

```typescript
function estimateObject3dSize(object: THREE.Object3D, parentSize?: MemoryUsage, visitedObjects?: Map<string, boolean>): MemoryUsage;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  object | THREE.Object3D | The mesh object to evaluate |
|  parentSize | [MemoryUsage](./harp-mapview.mapviewutils.memoryusage.md) |  |
|  visitedObjects | Map&lt;string, boolean&gt; | Optional map to store large objects that could be shared. |

<b>Returns:</b>

[MemoryUsage](./harp-mapview.mapviewutils.memoryusage.md)

Estimate of object size in bytes for heap and GPU.
