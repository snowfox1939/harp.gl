<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [MapViewOptions](./harp-mapview.mapviewoptions.md) &gt; [theme](./harp-mapview.mapviewoptions.theme.md)

## MapViewOptions.theme property

The \[\[Theme\]\] used by Mapview.

This Theme can be one of the following: - `string` : the URI of the theme file used to style this map - `Theme` : the `Theme` object already loaded - `Promise<Theme>` : the future `Theme` object - `undefined` : the theme is not yet set up, but can be set later. Rendering waits until the theme is set.

\*\*Note:\*\* Layers that use a theme do not render any content until that theme is available.

Relative URIs are resolved to full URL using the document's base URL (see: https://www.w3.org/TR/WD-html40-970917/htmlweb.html\#h-5.1.2).

Custom URIs (of theme itself and of resources referenced by theme) may be resolved with help of \[\[uriResolver\]\].

 \[\[ThemeLoader.load\]\] for details how theme is loaded

<b>Signature:</b>

```typescript
theme?: string | Theme | Promise<Theme>;
```