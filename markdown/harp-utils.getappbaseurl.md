<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-utils](./harp-utils.md) &gt; [getAppBaseUrl](./harp-utils.getappbaseurl.md)

## getAppBaseUrl() function

Get base URL for from where relative URLs will be loaded.

\* In browser, it resolves to `baseUrl(location.href)` i.e document's base URL (see: https://www.w3.org/TR/WD-html40-970917/htmlweb.html\#h-5.1.2).

\* In node, it resolves to `file://${process.cwd()}`<!-- -->.

<b>Signature:</b>

```typescript
export declare function getAppBaseUrl(): string;
```
<b>Returns:</b>

string
