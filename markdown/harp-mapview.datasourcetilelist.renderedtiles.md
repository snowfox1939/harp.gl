<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [DataSourceTileList](./harp-mapview.datasourcetilelist.md) &gt; [renderedTiles](./harp-mapview.datasourcetilelist.renderedtiles.md)

## DataSourceTileList.renderedTiles property

Map of tiles that will be rendered, key is the the combination of tile key and offset, see \[\[getKeyForTileKeyAndOffset\]\]. This includes tiles that are not in the \[\[visibleTiles\]\] list but that are used as fallbacks b/c they are still in the cache.

<b>Signature:</b>

```typescript
renderedTiles: Map<number, Tile>;
```