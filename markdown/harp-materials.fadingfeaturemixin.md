<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-materials](./harp-materials.md) &gt; [FadingFeatureMixin](./harp-materials.fadingfeaturemixin.md)

## FadingFeatureMixin class

Mixin class for extended THREE materials. Adds new properties required for `fadeNear` and `fadeFar`<!-- -->. There is some special handling for the fadeNear/fadeFar properties, which get some setters and getters in a way that works well with the mixin.

 \[\[Tile\#addRenderHelper\]\]

<b>Signature:</b>

```typescript
export declare class FadingFeatureMixin implements FadingFeature 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [defines](./harp-materials.fadingfeaturemixin.defines.md) |  | any |  |
|  [needsUpdate](./harp-materials.fadingfeaturemixin.needsupdate.md) |  | boolean |  |
|  [onBeforeCompile](./harp-materials.fadingfeaturemixin.onbeforecompile.md) |  | CompileCallback |  |
|  [shaderDefines](./harp-materials.fadingfeaturemixin.shaderdefines.md) |  | any |  |
|  [shaderUniforms](./harp-materials.fadingfeaturemixin.shaderuniforms.md) |  | UniformsType |  |
|  [uniformsNeedUpdate](./harp-materials.fadingfeaturemixin.uniformsneedupdate.md) |  | boolean |  |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [addFadingProperties()](./harp-materials.fadingfeaturemixin.addfadingproperties.md) |  | The mixin classes should call this method to register the properties \[\[fadeNear\]\] and \[\[fadeFar\]\]. |
|  [applyFadingParameters(params)](./harp-materials.fadingfeaturemixin.applyfadingparameters.md) |  | Apply the fadeNear/fadeFar values from the parameters to the respective properties. |
|  [copyFadingParameters(source)](./harp-materials.fadingfeaturemixin.copyfadingparameters.md) |  | Copy fadeNear/fadeFar values from other FadingFeature. |
|  [getFadeFar()](./harp-materials.fadingfeaturemixin.getfadefar.md) |  |  \[\[FadingFeature\#fadeFar\]\] |
|  [getFadeNear()](./harp-materials.fadingfeaturemixin.getfadenear.md) |  |  \[\[FadingFeature\#fadeNear\]\] |
|  [setFadeFar(value)](./harp-materials.fadingfeaturemixin.setfadefar.md) |  |  \[\[FadingFeature\#fadeFar\]\] |
|  [setFadeNear(value)](./harp-materials.fadingfeaturemixin.setfadenear.md) |  |  \[\[FadingFeature\#fadeNear\]\] |
