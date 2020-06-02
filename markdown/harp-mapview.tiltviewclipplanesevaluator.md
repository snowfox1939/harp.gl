<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [TiltViewClipPlanesEvaluator](./harp-mapview.tiltviewclipplanesevaluator.md)

## TiltViewClipPlanesEvaluator class

Evaluates camera clipping planes taking into account ground distance and camera angles.

This evaluator provides support for camera with varying tilt (pitch) angle, the angle between camera \_\_look at\_\_ vector and the ground surface normal.

<b>Signature:</b>

```typescript
export declare class TiltViewClipPlanesEvaluator extends TopViewClipPlanesEvaluator 
```

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [evaluateDistancePlanarProj(camera, projection, elevationProvider)](./harp-mapview.tiltviewclipplanesevaluator.evaluatedistanceplanarproj.md) |  |  |
|  [evaluateDistanceSphericalProj(camera, projection, elevationProvider)](./harp-mapview.tiltviewclipplanesevaluator.evaluatedistancesphericalproj.md) |  |  |
|  [getFrustumGroundIntersectionDist(camera, projection)](./harp-mapview.tiltviewclipplanesevaluator.getfrustumgroundintersectiondist.md) |  | Calculate the lengths of frustum planes intersection with the ground plane. This evaluates distances between eye vector (or eye plane in orthographic projection) and ground intersections of top and bottom frustum planes.  This method assumes the world surface (ground) to be flat and works only with planar projections. |
|  [getTiltedFovBasedFarPlane(d, r, halfFovAngle, cameraPitch)](./harp-mapview.tiltviewclipplanesevaluator.gettiltedfovbasedfarplane.md) |  |  |
