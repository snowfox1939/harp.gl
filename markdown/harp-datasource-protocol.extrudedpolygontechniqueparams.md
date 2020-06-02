<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [ExtrudedPolygonTechniqueParams](./harp-datasource-protocol.extrudedpolygontechniqueparams.md)

## ExtrudedPolygonTechniqueParams interface

Technique used to draw a geometry as an extruded polygon, for example extruded buildings.

<b>Signature:</b>

```typescript
export interface ExtrudedPolygonTechniqueParams extends StandardTechniqueParams 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [animateExtrusion](./harp-datasource-protocol.extrudedpolygontechniqueparams.animateextrusion.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;boolean&gt; | Animate the extrusion of the buildings if set to <code>true</code>. |
|  [animateExtrusionDuration](./harp-datasource-protocol.extrudedpolygontechniqueparams.animateextrusionduration.md) | number | Duration of the building's extrusion in milliseconds |
|  [boundaryWalls](./harp-datasource-protocol.extrudedpolygontechniqueparams.boundarywalls.md) | boolean | If <code>false</code>, wall geometry will not be added along the tile boundaries.  <code>true</code> |
|  [constantHeight](./harp-datasource-protocol.extrudedpolygontechniqueparams.constantheight.md) | boolean | If <code>true</code>, the height of the extruded buildings will not be modified by the mercator projection distortion that happens around the poles. <code>false</code> |
|  [defaultColor](./harp-datasource-protocol.extrudedpolygontechniqueparams.defaultcolor.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;[StyleColor](./harp-datasource-protocol.stylecolor.md)<!-- -->&gt; | Default color used if feature doesn't provide color attribute and \[\[MapEnv\]\] did not return it too.  color-hex |
|  [defaultHeight](./harp-datasource-protocol.extrudedpolygontechniqueparams.defaultheight.md) | number | In some data sources, for example Tilezen, building extrusion information might be missing. This attribute allows to define a default height of an extruded polygon in the theme. |
|  [enableDepthPrePass](./harp-datasource-protocol.extrudedpolygontechniqueparams.enabledepthprepass.md) | boolean | Control rendering of depth prepass before the actual geometry.<!-- -->Depth prepass is a method to render translucent meshes, hence only the visible front faces of a mesh are actually rendered, removing artifacts caused by blending with internal faces of the mesh. This method is used for drawing translucent buildings over map background.<!-- -->By default, each \[\[DataSource\]\] determines how/if enable the depth pre-pass. A value of <code>false</code> forcefully disables depth prepass. |
|  [floorHeight](./harp-datasource-protocol.extrudedpolygontechniqueparams.floorheight.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | Height of "floor" of extruded polygon in world units of extruded polygon.<!-- -->Usually, unique per feature, so defaults to <code>[&quot;number&quot;, [&quot;get&quot;, &quot;min_height&quot;], 0]</code>. |
|  [footprint](./harp-datasource-protocol.extrudedpolygontechniqueparams.footprint.md) | boolean | Renders the footprint lines if set to 'true'. |
|  [height](./harp-datasource-protocol.extrudedpolygontechniqueparams.height.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | Height above ground in world units of extruded polygon.<!-- -->Usually, unique per feature, so defaults to <code>[&quot;get&quot;, &quot;height&quot;]</code>. |
|  [lineColor](./harp-datasource-protocol.extrudedpolygontechniqueparams.linecolor.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;[StyleColor](./harp-datasource-protocol.stylecolor.md)<!-- -->&gt; | Fill color in hexadecimal or CSS-style notation, for example: <code>&quot;#e4e9ec&quot;</code>, <code>&quot;#fff&quot;</code>, <code>&quot;rgb(255, 0, 0)&quot;</code>, or <code>&quot;hsl(35, 11%, 88%)&quot;</code>.  color-hex |
|  [lineColorMix](./harp-datasource-protocol.extrudedpolygontechniqueparams.linecolormix.md) | number | Mix value between the lineColor(0.0) and the geometry's vertex colors(1.0). |
|  [lineFadeFar](./harp-datasource-protocol.extrudedpolygontechniqueparams.linefadefar.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | Distance to the camera (0.0 = nearPlane, 1.0 = farPlane) at which the object edges become transparent. A value of &lt;<!-- -->= 0.0 disables fading. |
|  [lineFadeNear](./harp-datasource-protocol.extrudedpolygontechniqueparams.linefadenear.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | Distance to the camera (0.0 = nearPlane, 1.0 = farPlane) at which the object edges start fading out. |
|  [lineWidth](./harp-datasource-protocol.extrudedpolygontechniqueparams.linewidth.md) | [DynamicProperty](./harp-datasource-protocol.dynamicproperty.md)<!-- -->&lt;number&gt; | Width of the lines. Currently limited to the \[0, 1\] range. |
|  [maxSlope](./harp-datasource-protocol.extrudedpolygontechniqueparams.maxslope.md) | number | Set to a negative value to remove all the vertical lines, and to a value between 0.0 and 1.0 to modulate the amount of vertical lines rendered. |
