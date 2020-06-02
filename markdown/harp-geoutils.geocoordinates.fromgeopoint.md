<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-geoutils](./harp-geoutils.md) &gt; [GeoCoordinates](./harp-geoutils.geocoordinates.md) &gt; [fromGeoPoint](./harp-geoutils.geocoordinates.fromgeopoint.md)

## GeoCoordinates.fromGeoPoint() method

Creates a \[\[GeoCoordinates\]\] from a \[\[GeoPointLike\]\] tuple.

Example:

```typescript
mapView.geoCenter = GeoCoordinates.fromGeoPoint([longitude, latitude]);

let geoCoords: number[] = ...;

if (isGeoPointLike(geoCoords)) {
    const p = GeoCoordinates.fromGeoPoint(geoCoords);
}

```

<b>Signature:</b>

```typescript
static fromGeoPoint(geoPoint: GeoPointLike): GeoCoordinates;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  geoPoint | [GeoPointLike](./harp-geoutils.geopointlike.md) | An \[\[Array\]\] of at least two elements following the order longitude, latitude, altitude. |

<b>Returns:</b>

[GeoCoordinates](./harp-geoutils.geocoordinates.md)
