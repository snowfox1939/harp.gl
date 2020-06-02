<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-utils](./harp-utils.md) &gt; [baseUrl](./harp-utils.baseurl.md)

## baseUrl() function

Returns base URL of given resource URL.

`Url` with trailing slash are considered genuine 'locations', they are returned as is, however if `url` ends with name component it is treated as "leaf", so last path component is removed.

Standalone files (without any folder structure) are considered relative to `./`<!-- -->.

Examples:

```
    https://foo.com/themes/a.json -> https://foo.com/themes/
    https://foo.com/themes/ -> https://foo.com/themes/
    https://foo.com/themes -> https://foo.com/ // note, themes is treated as leaf
    themes/day.json -> themes/
    themes -> ./

```

<b>Signature:</b>

```typescript
export declare function baseUrl(url: string | undefined): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  url | string \| undefined |  |

<b>Returns:</b>

string
