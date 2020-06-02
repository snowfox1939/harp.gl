<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapViewUtils](./harp-mapview.mapviewutils.md) &gt; [getGeoTargetFromCamera](./harp-mapview.mapviewutils.getgeotargetfromcamera.md)

## MapViewUtils.getGeoTargetFromCamera() function

> Warning: This API is now obsolete.
> 
> This function is for internal use only and will be removed in the future. Use MapView.worldTarget instead.
> 

Calculate target (focus) point geo-coordinates for given camera.  getTargetPositionFromCamera

<b>Signature:</b>

```typescript
function getGeoTargetFromCamera(camera: THREE.Camera, projection: Projection, elevation?: number): GeoCoordinates | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  camera | THREE.Camera | The camera looking on target point. |
|  projection | [Projection](./harp-geoutils.projection.md) | The geo-projection used. |
|  elevation | number | Optional elevation above (or below) sea level measured in world units. |

<b>Returns:</b>

[GeoCoordinates](./harp-geoutils.geocoordinates.md) \| null
