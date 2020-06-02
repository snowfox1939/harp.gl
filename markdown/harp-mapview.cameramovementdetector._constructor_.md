<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [CameraMovementDetector](./harp-mapview.cameramovementdetector.md) &gt; [(constructor)](./harp-mapview.cameramovementdetector._constructor_.md)

## CameraMovementDetector.(constructor)

Initializes the detector with timeout value and callbacks. \[\[MapView\]\] also provides events for client code to be notified when these cues occur.

<b>Signature:</b>

```typescript
constructor(m_throttlingTimeout: number | undefined, m_movementStartedFunc: (() => void) | undefined, m_movementFinishedFunc: (() => void) | undefined);
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  m\_throttlingTimeout | number \| undefined | The delay, in milliseconds, between the last user interaction detected and the call to <code>m_movementFinishedFunc</code>; the default is <code>300</code>. |
|  m\_movementStartedFunc | (() =&gt; void) \| undefined | Callback function, called when the user starts interacting. |
|  m\_movementFinishedFunc | (() =&gt; void) \| undefined | Callback function, called when the user stops interacting. |
