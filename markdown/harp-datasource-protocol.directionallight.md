<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [DirectionalLight](./harp-datasource-protocol.directionallight.md)

## DirectionalLight interface

Light type: directional.  \[ { "label": "New Directional Light", "description": "Adds a new Directional Light", "body": { "type": "directional", "name": "$<!-- -->{<!-- -->1:directional-light$:1<!-- -->}<!-- -->", "color": "\#$<!-- -->{<!-- -->2:fff<!-- -->}<!-- -->", "intensity": "^$<!-- -->{<!-- -->3:1<!-- -->}<!-- -->", "direction": { "x": "^$<!-- -->{<!-- -->4:1<!-- -->}<!-- -->", "y": "^$<!-- -->{<!-- -->5:0<!-- -->}<!-- -->", "z": "^$<!-- -->{<!-- -->6:0<!-- -->}<!-- -->" } } } \]

<b>Signature:</b>

```typescript
export interface DirectionalLight extends BaseLight 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [castShadow](./harp-datasource-protocol.directionallight.castshadow.md) | boolean |  |
|  [color](./harp-datasource-protocol.directionallight.color.md) | string |  color-hex |
|  [direction](./harp-datasource-protocol.directionallight.direction.md) | [Vector3Like](./harp-geoutils.vector3like.md) |  |
|  [intensity](./harp-datasource-protocol.directionallight.intensity.md) | number |  |
|  [type](./harp-datasource-protocol.directionallight.type.md) | "directional" |  |
