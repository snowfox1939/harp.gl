<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-utils](./harp-utils.md) &gt; [MathUtils](./harp-utils.mathutils.md)

## MathUtils namespace

<b>Signature:</b>

```typescript
export declare namespace MathUtils 
```

## Functions

|  Function | Description |
|  --- | --- |
|  [clamp(value, min, max)](./harp-utils.mathutils.clamp.md) | Ensures that input value fits in a given range. |
|  [easeInOutCubic(startValue, endValue, time)](./harp-utils.mathutils.easeinoutcubic.md) | Smoothly interpolates between two values using cubic formula |
|  [isClamped(value, lowerBound, upperBound)](./harp-utils.mathutils.isclamped.md) | Checks if the value of a given number is inside an upper or lower bound. The bounds may be undefined, in which case their value is ignored. |
|  [lerp(edge0, edge1, factor)](./harp-utils.mathutils.lerp.md) | Returns a linear interpolation between the values of edge0 and edge1 based on the factor.<!-- -->Given two known points the linear interpolant between these points may be presented as straight line. This means that for given factor change the resulting change of return value is always const.  https://en.wikipedia.org/wiki/Linear\_interpolation |
|  [map(val, inMin, inMax, outMin, outMax)](./harp-utils.mathutils.map.md) | Maps a number from one range to another. |
|  [max2(a, b)](./harp-utils.mathutils.max2.md) | Returns the larger of the two given numbers. Both numbers may be undefined, in which case the result is undefined. If only one of the numbers is undefined, the other number is returned. |
|  [min2(a, b)](./harp-utils.mathutils.min2.md) | Returns the smaller of the two given numbers. Both numbers may be undefined, in which case the result is undefined. If only one of the numbers is undefined, the other number is returned. |
|  [smootherStep(edge0, edge1, x)](./harp-utils.mathutils.smootherstep.md) | Returns a smooth interpolation between the values edge0 and edge1 based on the interpolation factor x. <code>0 &lt;= x &lt;= 1</code>.<!-- -->Improved version by Ken Perlin, which has zero 1st- and 2nd-order derivatives at <code>x = 0</code> and <code>x = 1</code>: https://en.wikipedia.org/wiki/Smoothstep |
|  [smoothStep(edge0, edge1, x)](./harp-utils.mathutils.smoothstep.md) | Returns a smooth interpolation between the values edge0 and edge1 based on the interpolation factor x. <code>0 &lt;= x &lt;= 1</code>.  https://en.wikipedia.org/wiki/Smoothstep |
