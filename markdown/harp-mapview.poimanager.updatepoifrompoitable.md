<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [PoiManager](./harp-mapview.poimanager.md) &gt; [updatePoiFromPoiTable](./harp-mapview.poimanager.updatepoifrompoitable.md)

## PoiManager.updatePoiFromPoiTable() method

Update the \[\[TextElement\]\] with the information taken from the \[\[PoiTable\]\] which is referenced in the \[\[PoiInfo\]\] of the pointLabel.

If the requested \[\[PoiTable\]\] is not available yet, the function returns `false`<!-- -->. If the \[\[PoiTable\]\] is not defined, or if the references POI has no entry in the \[\[PoiTable\]\], no action is taken, and the function returns `false`<!-- -->.

If the \[\[PoiTable\]\] has been processed, it returns `true`<!-- -->, indicating that this function doesn't have to be called again.

<b>Signature:</b>

```typescript
updatePoiFromPoiTable(pointLabel: TextElement): boolean;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  pointLabel | [TextElement](./harp-mapview.textelement.md) | The \[\[TextElement\]\] to update. |

<b>Returns:</b>

boolean

`true` if the \[\[PoiTable\]\] has been processed, and the function does not have to be called again.
