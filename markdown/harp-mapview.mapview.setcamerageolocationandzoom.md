<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapView](./harp-mapview.mapview.md) &gt; [setCameraGeolocationAndZoom](./harp-mapview.mapview.setcamerageolocationandzoom.md)

## MapView.setCameraGeolocationAndZoom() method

> Warning: This API is now obsolete.
> 
> Use \[\[MapView.lookAt\]\] instead.
> 

Moves the camera to the specified \[\[GeoCoordinates\]\], sets the desired `zoomLevel` and adjusts the yaw and pitch. The pitch of the camera is always curbed so that the camera cannot look above the horizon. This paradigm is necessary in \[\[MapControls\]\], where the center of \\ the screen is used for the orbiting interaction (3 fingers / right mouse button).

<b>Signature:</b>

```typescript
setCameraGeolocationAndZoom(geoPos: GeoCoordinates, zoomLevel: number, yawDeg?: number, pitchDeg?: number): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  geoPos | [GeoCoordinates](./harp-geoutils.geocoordinates.md) | Geolocation to move the camera to. |
|  zoomLevel | number | Desired zoom level. |
|  yawDeg | number | Camera yaw in degrees, counter-clockwise (as opposed to heading), starting north. |
|  pitchDeg | number | Camera pitch in degrees. |

<b>Returns:</b>

void
