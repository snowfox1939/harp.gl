<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [TextElement](./harp-mapview.textelement.md) &gt; [(constructor)](./harp-mapview.textelement._constructor_.md)

## TextElement.(constructor)

Creates a new `TextElement`<!-- -->.

<b>Signature:</b>

```typescript
constructor(text: string, points: THREE.Vector3[] | THREE.Vector3, renderParams: TextRenderParameters | TextRenderStyle, layoutParams: TextLayoutParameters | TextLayoutStyle, priority?: number, xOffset?: number, yOffset?: number, featureId?: number | undefined, style?: string | undefined, fadeNear?: number | undefined, fadeFar?: number | undefined, tileOffset?: number | undefined, offsetDirection?: number | undefined);
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  text | string | The text to display. |
|  points | THREE.Vector3\[\] \| THREE.Vector3 | The position or a list of points for a curved text, both in world space. |
|  renderParams | [TextRenderParameters](./harp-text-canvas.textrenderparameters.md) \| [TextRenderStyle](./harp-text-canvas.textrenderstyle.md) | <code>TextElement</code> text rendering parameters. |
|  layoutParams | [TextLayoutParameters](./harp-text-canvas.textlayoutparameters.md) \| [TextLayoutStyle](./harp-text-canvas.textlayoutstyle.md) | <code>TextElement</code> text layout parameters. |
|  priority | number | The priority of the <code>TextElement. Elements with the highest priority get placed first, elements with priority of </code>0<!-- -->\` are placed last, elements with a negative value are always rendered, ignoring priorities and allowing overrides. |
|  xOffset | number | Optional X offset of this <code>TextElement</code> in screen coordinates. |
|  yOffset | number | Optional Y offset of this <code>TextElement</code> in screen coordinates. |
|  featureId | number \| undefined | Optional number to identify feature (originated from <code>OmvDataSource</code>). |
|  style | string \| undefined |  |
|  fadeNear | number \| undefined | Distance to the camera (0.0 = camera position, 1.0 = farPlane) at which the label starts fading out (opacity decreases). |
|  fadeFar | number \| undefined | Distance to the camera (0.0 = camera position, 1.0 = farPlane) at which the label becomes transparent. A value of &lt;<!-- -->= 0.0 disables fading. |
|  tileOffset | number \| undefined |  |
|  offsetDirection | number \| undefined | Direction represented as an angle in degrees clockwise from north to offset the icon in world space. |
