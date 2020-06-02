<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapViewAtmosphere](./harp-mapview.mapviewatmosphere.md)

## MapViewAtmosphere class

Class that provides \[\[MapView\]\]'s atmospheric scattering effect.

<b>Signature:</b>

```typescript
export declare class MapViewAtmosphere 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(m\_sceneRoot, m\_sceneCamera, m\_projection, m\_updateCallback, m\_atmosphereVariant, m\_materialVariant)](./harp-mapview.mapviewatmosphere._constructor_.md) |  | Creates and adds <code>Atmosphere</code> effects to the scene. Currently works only with globe projection. |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [enabled](./harp-mapview.mapviewatmosphere.enabled.md) |  | boolean | Returns the current atmosphere status, enabled or disabled. |
|  [GroundAtmosphereUserName](./harp-mapview.mapviewatmosphere.groundatmosphereusername.md) | <code>static</code> | string | User data name attribute assigned to created mesh. |
|  [groundMesh](./harp-mapview.mapviewatmosphere.groundmesh.md) |  | THREE.Mesh \| undefined |  |
|  [SkyAtmosphereUserName](./harp-mapview.mapviewatmosphere.skyatmosphereusername.md) | <code>static</code> | string | User data name attribute assigned to created mesh. |
|  [skyMesh](./harp-mapview.mapviewatmosphere.skymesh.md) |  | THREE.Mesh \| undefined |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [dispose()](./harp-mapview.mapviewatmosphere.dispose.md) |  | Disposes allocated resources. |
|  [isPresent(where)](./harp-mapview.mapviewatmosphere.ispresent.md) | <code>static</code> | Check if scene or root scene object has already atmosphere effect added. |
|  [reset(theme)](./harp-mapview.mapviewatmosphere.reset.md) |  | Sets the atmosphere depending on the \[\[Theme\]\] instance provided.<!-- -->This function is called when a theme is loaded. Atmosphere is added only if the theme contains a atmosphere definition with a: - <code>color</code> property, used to set the atmosphere color. |
