<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [ConcurrentDecoderFacade](./harp-mapview.concurrentdecoderfacade.md) &gt; [getTileDecoder](./harp-mapview.concurrentdecoderfacade.gettiledecoder.md)

## ConcurrentDecoderFacade.getTileDecoder() method

Returns a \[\[WorkerBasedDecoder\]\] instance.

<b>Signature:</b>

```typescript
static getTileDecoder(decoderServiceType: string, scriptUrl?: string, workerCount?: number): ITileDecoder;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  decoderServiceType | string | The name of the decoder service type. |
|  scriptUrl | string | The optional URL with the workers' script. |
|  workerCount | number | The number of web workers to use. |

<b>Returns:</b>

[ITileDecoder](./harp-datasource-protocol.itiledecoder.md)
