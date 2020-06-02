<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [CameraMovementDetector](./harp-mapview.cameramovementdetector.md) &gt; [cameraIsMoving](./harp-mapview.cameramovementdetector.cameraismoving.md)

## CameraMovementDetector.cameraIsMoving property

Returns `true` if the camera of this \[\[MapView\]\] is currently moving. In this case the `m_movementFinishedFunc` is waiting to be called after the throttling timer runs out.

<b>Signature:</b>

```typescript
get cameraIsMoving(): boolean;
```