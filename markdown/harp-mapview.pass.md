<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [Pass](./harp-mapview.pass.md)

## Pass class

The base class to extend for further passes in \[\[MapView\]\], like the \[\[MSAARenderPass\]\], possibly a text pass, an AO effect etc. `Pass` provides the core logic for both : - render passes (proper scene renders), - and shader passes (quad renders, i.e. effects added on top of the render output as a postprocess).

Even some shader passes still actually fall within the render pass category as they need to re-render the scene to then deduce an effect, such as masking, AO, DoF etc. Others just need the previous input image to apply a shader on top of it, as for bloom or NVIDIA's FXAA for example. These only are proper shader passes.

<b>Signature:</b>

```typescript
export declare class Pass implements IPass 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [enabled](./harp-mapview.pass.enabled.md) |  | boolean |  |
|  [renderToScreen](./harp-mapview.pass.rendertoscreen.md) |  | boolean |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [render(renderer, scene, camera, writeBuffer, readBuffer, delta)](./harp-mapview.pass.render.md) |  |  |
|  [setSize(width, height)](./harp-mapview.pass.setsize.md) |  |  |
