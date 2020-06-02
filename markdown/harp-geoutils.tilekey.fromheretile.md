<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-geoutils](./harp-geoutils.md) &gt; [TileKey](./harp-geoutils.tilekey.md) &gt; [fromHereTile](./harp-geoutils.tilekey.fromheretile.md)

## TileKey.fromHereTile() method

Creates a tile key from a heretile code string.

The string can be created with \[\[toHereTile\]\].

<b>Signature:</b>

```typescript
static fromHereTile(quadkey64: string): TileKey;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  quadkey64 | string | The string representation of the HERE tile key. |

<b>Returns:</b>

[TileKey](./harp-geoutils.tilekey.md)

A new instance of `TileKey`<!-- -->.
