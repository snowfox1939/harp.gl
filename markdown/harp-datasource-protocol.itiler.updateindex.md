<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [ITiler](./harp-datasource-protocol.itiler.md) &gt; [updateIndex](./harp-datasource-protocol.itiler.updateindex.md)

## ITiler.updateIndex() method

Update index in the tiler. Indexes registered in the tiler can be later used to retrieved tiled payloads using `getTile`<!-- -->.

<b>Signature:</b>

```typescript
updateIndex(indexId: string, indexUrl: URL | GeoJson): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  indexId | string | Index identifier. |
|  indexUrl | URL \| [GeoJson](./harp-datasource-protocol.geojson.md) | Url to the index payload, or direct GeoJson. |

<b>Returns:</b>

Promise&lt;void&gt;
