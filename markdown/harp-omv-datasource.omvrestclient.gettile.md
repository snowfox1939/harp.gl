<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-omv-datasource](./harp-omv-datasource.md) &gt; [OmvRestClient](./harp-omv-datasource.omvrestclient.md) &gt; [getTile](./harp-omv-datasource.omvrestclient.gettile.md)

## OmvRestClient.getTile() method

Asynchronously fetches a tile from this restful server.

\*\*Note:\*\* If the tile doesn't exist, a successful response with a `404` status code is returned.

<b>Signature:</b>

```typescript
getTile(tileKey: TileKey, abortSignal?: AbortSignal | undefined): Promise<ArrayBufferLike | {}>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  tileKey | [TileKey](./harp-geoutils.tilekey.md) | The tile key of the tile. |
|  abortSignal | AbortSignal \| undefined |  |

<b>Returns:</b>

Promise&lt;ArrayBufferLike \| {}&gt;

A `Promise` of the HTTP response that contains the payload of the requested tile.

## Example


```typescript
const response = layer.getTile(tileKey);
if (!response.ok) {
    // a network error happened
    console.error("Unable to download tile", response.statusText);
    return;
}
if (response.status === 404) {
    // 404 -, no data exists at the given tile. Do nothing.
    return;
}

// the response is ok and contains data, access it e.g. as arrayBuffer:
const payload = await response.arrayBuffer();

```
