<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [IPass](./harp-mapview.ipass.md)

## IPass interface

The interface for the \[\[Pass\]\] class.

<b>Signature:</b>

```typescript
export interface IPass 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [enabled](./harp-mapview.ipass.enabled.md) | boolean | Whether the \[\[Pass\]\] instance is active or not.  <code>true</code>. |
|  [renderToScreen](./harp-mapview.ipass.rendertoscreen.md) | boolean | Whether the render method should target a WebGLRenderTarget instance, or the frame buffer.  <code>false</code>. |

## Methods

|  Method | Description |
|  --- | --- |
|  [render(renderer, scene, camera, writeBuffer, readBuffer, delta)](./harp-mapview.ipass.render.md) | The render method to extend in \[\[Pass\]\] implementations. This is the place where the desired effects or render operations are executed. |
|  [setSize(width, height)](./harp-mapview.ipass.setsize.md) | The resize method to extend in \[\[Pass\]\] implementations. It resizes the render targets. Call on resize events. |
