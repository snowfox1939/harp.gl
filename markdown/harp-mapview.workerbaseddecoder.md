<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [WorkerBasedDecoder](./harp-mapview.workerbaseddecoder.md)

## WorkerBasedDecoder class

Decoder based on \[\[ConcurrentWorkerSet\]\].

Decodes tiles using workers running in separate contexts (also known as `WebWorkers`<!-- -->): - connection establishment, - sends decode requests, - configuration.

<b>Signature:</b>

```typescript
export declare class WorkerBasedDecoder implements ITileDecoder 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(workerSet, decoderServiceType)](./harp-mapview.workerbaseddecoder._constructor_.md) |  | Creates a new <code>WorkerBasedDecoder</code>. |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [workerCount](./harp-mapview.workerbaseddecoder.workercount.md) |  | number \| undefined | The number of workers started for this decoder. The value is <code>undefined</code> until the workers have been created. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [configure(styleSet, definitions, languages, options)](./harp-mapview.workerbaseddecoder.configure.md) |  | Configure tile decoder service in workers.<!-- -->Broadcasts \[\[ConfigurationMessage\]\] to all \[\[TileDecoderService\]\]s running in worker pool. |
|  [connect()](./harp-mapview.workerbaseddecoder.connect.md) |  | Connects to \[\[WorkerServiceManager\]\]s in underlying \[\[ConcurrentWorkerSet\]\] and creates dedicated \[\[TileDecoderService\]\]s in all workers to serve decode requests. |
|  [decodeTile(data, tileKey, projection, requestController)](./harp-mapview.workerbaseddecoder.decodetile.md) |  | Get \[\[Tile\]\] from tile decoder service in worker.<!-- -->Invokes \[\[DecodeTileRequest\]\] on \[\[TileDecoderService\]\] running in worker pool. |
|  [dispose()](./harp-mapview.workerbaseddecoder.dispose.md) |  | Dispose of dedicated tile decoder services in workers and remove reference to underlying \[\[ConcurrentWorkerSet\]\]. |
|  [getTileInfo(data, tileKey, projection, requestController)](./harp-mapview.workerbaseddecoder.gettileinfo.md) |  | Get \[\[TileInfo\]\] from tile decoder service in worker.<!-- -->Invokes \[\[TileInfoRequest\]\] on \[\[TileDecoderService\]\] running in worker pool. |
