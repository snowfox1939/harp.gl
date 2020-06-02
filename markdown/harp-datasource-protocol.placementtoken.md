<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [PlacementToken](./harp-datasource-protocol.placementtoken.md)

## PlacementToken enum

Defines options (tokens) supported for text placements defined via \[\[placements\]\] attribute.

Possible values are defined as vertical placement letter and horizontal letter, where one of the axis may be ignored and then assumed centered. Moving clock-wise, we have: `TL` (top-left), `T` (top-center), `TR` (top-right), `R` (center-right), `BR` (bottom-right), `B` (bottom-center), `BL` (bottom-left), `L` (left), `C` (center-center). Alternatively instead of `T`<!-- -->, `B`<!-- -->, `L`<!-- -->, `R` geographic directions may be used accordingly: `NW` (north-west), `N` (north), `NE` (north-east), `E` (east), `SE` (south-east), `S` (south), `SW` (south-west), `W` (west).

<b>Signature:</b>

```typescript
export declare enum PlacementToken 
```

## Enumeration Members

|  Member | Value | Description |
|  --- | --- | --- |
|  Bottom | <code>&quot;B&quot;</code> |  |
|  BottomLeft | <code>&quot;BL&quot;</code> |  |
|  BottomRight | <code>&quot;BR&quot;</code> |  |
|  Center | <code>&quot;C&quot;</code> |  |
|  East | <code>&quot;E&quot;</code> |  |
|  Left | <code>&quot;L&quot;</code> |  |
|  North | <code>&quot;N&quot;</code> |  |
|  NorthEast | <code>&quot;NE&quot;</code> |  |
|  NorthWest | <code>&quot;NW&quot;</code> |  |
|  Right | <code>&quot;R&quot;</code> |  |
|  South | <code>&quot;S&quot;</code> |  |
|  SouthEast | <code>&quot;SE&quot;</code> |  |
|  SouthWest | <code>&quot;SW&quot;</code> |  |
|  Top | <code>&quot;T&quot;</code> |  |
|  TopLeft | <code>&quot;TL&quot;</code> |  |
|  TopRight | <code>&quot;TR&quot;</code> |  |
|  West | <code>&quot;W&quot;</code> |  |
