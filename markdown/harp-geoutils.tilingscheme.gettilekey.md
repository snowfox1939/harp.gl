<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-geoutils](./harp-geoutils.md) &gt; [TilingScheme](./harp-geoutils.tilingscheme.md) &gt; [getTileKey](./harp-geoutils.tilingscheme.gettilekey.md)

## TilingScheme.getTileKey() method

Gets the \[\[TileKey\]\] from the given geo position and level.

<b>Signature:</b>

```typescript
getTileKey(geoPoint: GeoCoordinatesLike, level: number): TileKey | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  geoPoint | [GeoCoordinatesLike](./harp-geoutils.geocoordinateslike.md) | The position in geo coordinates. |
|  level | number | The level of the resulting <code>TileKey</code>. |

<b>Returns:</b>

[TileKey](./harp-geoutils.tilekey.md) \| null
