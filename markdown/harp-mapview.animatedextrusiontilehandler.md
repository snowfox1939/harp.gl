<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [AnimatedExtrusionTileHandler](./harp-mapview.animatedextrusiontilehandler.md)

## AnimatedExtrusionTileHandler class

Implements animated extrusion effect for the extruded objects in the \[\[Tile\]\]

<b>Signature:</b>

```typescript
export declare class AnimatedExtrusionTileHandler 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(m\_tile, extrudedObjects, m\_animatedExtrusionDuration)](./harp-mapview.animatedextrusiontilehandler._constructor_.md) |  | Constructs a new instance of the <code>AnimatedExtrusionTileHandler</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [animationState](./harp-mapview.animatedextrusiontilehandler.animationstate.md) |  | [AnimatedExtrusionState](./harp-mapview.animatedextrusionstate.md) | Return the current state of animated extrusion effect |
|  [isAnimating](./harp-mapview.animatedextrusiontilehandler.isanimating.md) |  | boolean | Is <code>true</code> if this handler is currently animating. |
|  [tile](./harp-mapview.animatedextrusiontilehandler.tile.md) |  | [Tile](./harp-mapview.tile.md) | Returns the \[\[Tile\]\] related to \[\[AnimatedExtrusionTileHandler\]\] |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [dispose()](./harp-mapview.animatedextrusiontilehandler.dispose.md) |  | Cancel animation and remove from \[\[AnimatedExtrusionHandler\]\] |
|  [zoomLevelChanged(zoomDirection)](./harp-mapview.animatedextrusiontilehandler.zoomlevelchanged.md) |  | Start / Stop extrusion animation if zoom level was changed |
