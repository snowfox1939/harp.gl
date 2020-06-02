<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [parseStringEncodedNumeral](./harp-datasource-protocol.parsestringencodednumeral.md)

## parseStringEncodedNumeral() function

Parse string encoded numeral values using all known \[\[StringEncodedNumeralFormats\]\].

<b>Signature:</b>

```typescript
export declare function parseStringEncodedNumeral(numeral: string, pixelToMeters?: number): number | undefined;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  numeral | string | The string representing numeric value. |
|  pixelToMeters | number | The ratio used to convert from meters to pixels (default 1.0). |

<b>Returns:</b>

number \| undefined

Number parsed or \_\_undefined\_\_ if non of the numeral patterns matches the expression provided in \[\[numeral\]\].
