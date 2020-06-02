<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [ColorCache](./harp-mapview.colorcache.md)

## ColorCache class

Use `ColorCache` to reuse a color specified by name and save allocation as well as setup time.

Implemented as a singleton. Do not modify colors after getting them from the `ColorCache`<!-- -->.

<b>Signature:</b>

```typescript
export declare class ColorCache 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [instance](./harp-mapview.colorcache.instance.md) | <code>static</code> | [ColorCache](./harp-mapview.colorcache.md) | Return instance of <code>ColorCache</code>. |
|  [size](./harp-mapview.colorcache.size.md) |  | number | Returns the number of elements in the cache. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [clear()](./harp-mapview.colorcache.clear.md) |  | Clears the cache. Only references to the THREE.Color are removed from the cache. Consequently, clearing the cache does not cause any negative visual impact. |
|  [getColor(colorCode)](./harp-mapview.colorcache.getcolor.md) |  | Returns the color for the given <code>colorCode</code>. This function may reuse a previously generated color, so you cannot modify the contents of the color. |
