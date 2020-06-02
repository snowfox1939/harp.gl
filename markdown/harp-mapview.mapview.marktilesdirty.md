<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapView](./harp-mapview.mapview.md) &gt; [markTilesDirty](./harp-mapview.mapview.marktilesdirty.md)

## MapView.markTilesDirty() method

Visit each tile in visible, rendered, and cached sets.

\* Visible and temporarily rendered tiles will be marked for update and retained. \* Cached but not rendered/visible will be evicted.

<b>Signature:</b>

```typescript
markTilesDirty(dataSource?: DataSource): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  dataSource | [DataSource](./harp-mapview.datasource.md) | If passed, only the tiles from this \[\[DataSource\]\] instance are processed. If <code>undefined</code>, tiles from all \[\[DataSource\]\]s are processed. |

<b>Returns:</b>

void
