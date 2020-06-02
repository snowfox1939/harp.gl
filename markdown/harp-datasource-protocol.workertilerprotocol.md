<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [WorkerTilerProtocol](./harp-datasource-protocol.workertilerprotocol.md)

## WorkerTilerProtocol namespace

Communication protocol with \[\[ITiler\]\].

<b>Signature:</b>

```typescript
export declare namespace WorkerTilerProtocol 
```

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [Requests](./harp-datasource-protocol.workertilerprotocol.requests.md) | Define possible names of requests called on tiler services within <code>WebWorker</code>. |

## Functions

|  Function | Description |
|  --- | --- |
|  [isRegisterIndexRequest(message)](./harp-datasource-protocol.workertilerprotocol.isregisterindexrequest.md) | Type guard to check if an object is an index registration request sent to a worker. |
|  [isTileRequest(message)](./harp-datasource-protocol.workertilerprotocol.istilerequest.md) | Type guard to check if an object is a tile request sent to a worker. |
|  [isUpdateIndexRequest(message)](./harp-datasource-protocol.workertilerprotocol.isupdateindexrequest.md) | Type guard to check if an object is an update request for the index registration. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [RegisterIndexRequest](./harp-datasource-protocol.workertilerprotocol.registerindexrequest.md) | This object is sent to the tiler to register a new tile index in the worker. |
|  [TileRequest](./harp-datasource-protocol.workertilerprotocol.tilerequest.md) | This object is sent to the tiler asking to retrieve a specific tile. The expected response type is an object containing a tiled payload. |
|  [UpdateIndexRequest](./harp-datasource-protocol.workertilerprotocol.updateindexrequest.md) | This object is sent to the tiler to register a new tile index in the worker. |
