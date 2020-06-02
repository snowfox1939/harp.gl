<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-text-canvas](./harp-text-canvas.md)

## harp-text-canvas package

## Classes

|  Class | Description |
|  --- | --- |
|  [ContextualArabicConverter](./harp-text-canvas.contextualarabicconverter.md) | Converter between arabic isolated forms (in Unicode Block 'Arabic') and their contextual forms (in Unicode Block 'Arabic Presentation Forms-B'). |
|  [FontCatalog](./harp-text-canvas.fontcatalog.md) | Collection of font assets used to render glyphs when using a \[\[TextCanvas\]\]. A <code>FontCatalog</code> works as a stack of SDF bitmap fonts (using the BMFont format) designed to cover the widest Unicode code point range possible. In order to manage all these assets elegantly, the assets inside the <code>FontCatalog</code> are stored on a per-Unicode-Block basis, and assets for a block are only loaded once a glyph belonging to that block is requested.<!-- -->Bitmap information coming from all different fonts is then stored in a unified WebGL GPU Texture resource, which can be sampled to render all currently loaded glyphs. |
|  [GlyphData](./harp-text-canvas.glyphdata.md) | Structure containing all the required information necessary to render a BMFont glyph using \[\[TextCanvas\]\]. |
|  [TextBufferObject](./harp-text-canvas.textbufferobject.md) | Object containing vertex buffer data generated by \[\[TextCanvas\]\]. |
|  [TextCanvas](./harp-text-canvas.textcanvas.md) | three.js text rendering engine which can manage and render high-quality, transformable, stylable and properly layout SDF and MSDF text. |
|  [TextLayoutStyle](./harp-text-canvas.textlayoutstyle.md) | \[\[TextCanvas\]\] text rendering style. |
|  [TextRenderStyle](./harp-text-canvas.textrenderstyle.md) | \[\[TextCanvas\]\] text rendering style. |

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [FontStyle](./harp-text-canvas.fontstyle.md) | Style to be used when rendering glyphs. |
|  [FontUnit](./harp-text-canvas.fontunit.md) | Unit of measurement used to specify a font's size. |
|  [FontVariant](./harp-text-canvas.fontvariant.md) | Variant to be used when rendering. |
|  [HorizontalAlignment](./harp-text-canvas.horizontalalignment.md) | Horizontal alignment to be used when placing text. |
|  [HorizontalPlacement](./harp-text-canvas.horizontalplacement.md) | Horizontal position of text element relative to the placement context (point, line). \[\[HorizontalPlacement\]\] value is exactly opposite to \[\[HorizontalAlignment\]\] value, cause when you place text on the right side of point (or icon) it will be left-aligned. |
|  [VerticalAlignment](./harp-text-canvas.verticalalignment.md) | Vertical alignment to be used when placing text. |
|  [VerticalPlacement](./harp-text-canvas.verticalplacement.md) | Vertical position of text area relative to the placement context (point, line). |
|  [WrappingMode](./harp-text-canvas.wrappingmode.md) | Text wrapping rule used when <code>lineWidth</code> is reached. |

## Functions

|  Function | Description |
|  --- | --- |
|  [createSdfTextMaterial(params)](./harp-text-canvas.createsdftextmaterial.md) | Helper function designed to create \[\[SdfTextMaterials\]\] that can be rendered using \[\[TextCanvas\]\]. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [AdditionParameters](./harp-text-canvas.additionparameters.md) | Optional parameters passed on \[\[TextCanvas\]\].<code>addText</code> function call. |
|  [Font](./harp-text-canvas.font.md) | Description of all assets, charset and metrics that define a font inside a \[\[FontCatalog\]\]. |
|  [FontMetrics](./harp-text-canvas.fontmetrics.md) | Metrics defining the placement and rendering of all glyphs in a given \[\[Font\]\]. |
|  [FontSize](./harp-text-canvas.fontsize.md) | Pair of unit and size specifying a font's size. |
|  [MeasurementParameters](./harp-text-canvas.measurementparameters.md) | Optional parameters passed on \[\[TextCanvas\]\].<code>measureText</code> function call. |
|  [MemoryUsage](./harp-text-canvas.memoryusage.md) | Describes estimated usage of memory on heap and GPU. |
|  [SdfTextMaterialParameters](./harp-text-canvas.sdftextmaterialparameters.md) | Material parameters passed on \[\[SdfTextMaterial\]\] creation when using the <code> </code>createSdfTextMaterial<!-- -->\` helper function. |
|  [TextBufferAdditionParameters](./harp-text-canvas.textbufferadditionparameters.md) | Optional parameters passed on \[\[TextCanvas\]\].<code>addTextBufferObject</code> function call. |
|  [TextBufferCreationParameters](./harp-text-canvas.textbuffercreationparameters.md) | Optional parameters passed on \[\[TextCanvas\]\].<code>createTextBufferObject</code> function call. |
|  [TextCanvasLayer](./harp-text-canvas.textcanvaslayer.md) | \[\[TextCanvas\]\] rendering layer. |
|  [TextCanvasParameters](./harp-text-canvas.textcanvasparameters.md) | \[\[TextCanvas\]\] construction parameters. |
|  [TextLayoutParameters](./harp-text-canvas.textlayoutparameters.md) | \[\[TextCanvas\]\] text layout parameters. |
|  [TextPlacement](./harp-text-canvas.textplacement.md) |  |
|  [TextRenderParameters](./harp-text-canvas.textrenderparameters.md) | \[\[TextCanvas\]\] text rendering parameters. |
|  [UnicodeBlock](./harp-text-canvas.unicodeblock.md) | Description of a continuous range of Unicode code points (as well as information on which fonts supports it). |

## Namespaces

|  Namespace | Description |
|  --- | --- |
|  [DefaultTextStyle](./harp-text-canvas.defaulttextstyle.md) | Namespace containing default values for all members of \[\[TextRenderParameters\]\] and \[\[TextLayoutParameters\]\]. |
|  [TypesettingUtils](./harp-text-canvas.typesettingutils.md) | Collection of different constants and utility functions used by \[\[Typesetter\]\]s. |
|  [UnicodeUtils](./harp-text-canvas.unicodeutils.md) | Namespace containing useful information when dealing with Unicode's code points. |

## Variables

|  Variable | Description |
|  --- | --- |
|  [DEFAULT\_TEXT\_CANVAS\_LAYER](./harp-text-canvas.default_text_canvas_layer.md) | Default's \[\[TextCanvas\]\] layer identifier. |

## Type Aliases

|  Type Alias | Description |
|  --- | --- |
|  [TextPlacements](./harp-text-canvas.textplacements.md) |  |
