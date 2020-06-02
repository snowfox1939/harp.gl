<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapViewUtils](./harp-mapview.mapviewutils.md) &gt; [calculateDistanceFromZoomLevel](./harp-mapview.mapviewutils.calculatedistancefromzoomlevel.md)

## MapViewUtils.calculateDistanceFromZoomLevel() function

Calculates and returns the distance to the target point.

<b>Signature:</b>

```typescript
function calculateDistanceFromZoomLevel(options: {
        focalLength: number;
    }, zoomLevel: number): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | { focalLength: number; } | Necessary subset of MapView properties to compute the distance. |
|  zoomLevel | number | The zoom level to get the equivalent height to. |

<b>Returns:</b>

number
