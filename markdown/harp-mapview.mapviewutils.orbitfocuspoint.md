<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapViewUtils](./harp-mapview.mapviewutils.md) &gt; [orbitFocusPoint](./harp-mapview.mapviewutils.orbitfocuspoint.md)

## MapViewUtils.orbitFocusPoint() function

Orbits the camera around the focus point of the camera.

<b>Signature:</b>

```typescript
function orbitFocusPoint(mapView: MapView, deltaAzimuthDeg: number, deltaTiltDeg: number, maxTiltAngleRad?: number): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  mapView | [MapView](./harp-mapview.mapview.md) | The \[\[MapView\]\] instance to manipulate. |
|  deltaAzimuthDeg | number | Delta azimuth in degrees. |
|  deltaTiltDeg | number | Delta tilt in degrees. |
|  maxTiltAngleRad | number | The maximum tilt between the camera and its target in radian. |

<b>Returns:</b>

void
