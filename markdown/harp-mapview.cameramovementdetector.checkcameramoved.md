<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [CameraMovementDetector](./harp-mapview.cameramovementdetector.md) &gt; [checkCameraMoved](./harp-mapview.cameramovementdetector.checkcameramoved.md)

## CameraMovementDetector.checkCameraMoved() method

Checks if the camera has moved since the last time it was checked. The `m_movementStartedFunc` is called when a movement starts. If no movement is detected, a timer for `m_movementFinishedFunc` starts.

<b>Signature:</b>

```typescript
checkCameraMoved(mapView: MapView, now: number): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  mapView | [MapView](./harp-mapview.mapview.md) | \[\[Mapview\]\]'s position and camera are checked for modifications. |
|  now | number |  |

<b>Returns:</b>

boolean
