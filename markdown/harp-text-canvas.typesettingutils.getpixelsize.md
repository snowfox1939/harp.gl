<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-text-canvas](./harp-text-canvas.md) &gt; [TypesettingUtils](./harp-text-canvas.typesettingutils.md) &gt; [getPixelSize](./harp-text-canvas.typesettingutils.getpixelsize.md)

## TypesettingUtils.getPixelSize() function

Convert between any size specified in any \[\[FontUnit\]\] to pixels.

<b>Signature:</b>

```typescript
function getPixelSize(size: number, unit: FontUnit, originalSize: number): number;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  size | number | Font size (specified in <code>unit</code>). |
|  unit | [FontUnit](./harp-text-canvas.fontunit.md) | Size unit. |
|  originalSize | number | Original size (pixels) |

<b>Returns:</b>

number

Pixel size.
