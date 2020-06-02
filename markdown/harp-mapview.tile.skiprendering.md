<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [Tile](./harp-mapview.tile.md) &gt; [skipRendering](./harp-mapview.tile.skiprendering.md)

## Tile.skipRendering property

If the tile should not be rendered, this is used typically when the tile in question is completely covered by another tile and therefore can be skipped without any visual impact. Setting this value directly affects the \[\[willRender\]\] method, unless overriden by deriving classes.

<b>Signature:</b>

```typescript
skipRendering: boolean;
```