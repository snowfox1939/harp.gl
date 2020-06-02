<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-transfer-manager](./harp-transfer-manager.md) &gt; [TransferManager](./harp-transfer-manager.transfermanager.md) &gt; [downloadJson](./harp-transfer-manager.transfermanager.downloadjson.md)

## TransferManager.downloadJson() method

Downloads a JSON object. Merges downloads if requested multiple times.

Note: This method merges multiple downloads of the same string URL to only one request. The init parameter is ignored if the download is merged. Call \[\[download\]\] instead to download the resource without merging.

<b>Signature:</b>

```typescript
downloadJson<T>(url: RequestInfo, init?: RequestInit): Promise<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  url | RequestInfo | The URL to download |
|  init | RequestInit | Optional extra parameters for the download. |

<b>Returns:</b>

Promise&lt;T&gt;
