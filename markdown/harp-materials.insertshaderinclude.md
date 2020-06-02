<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-materials](./harp-materials.md) &gt; [insertShaderInclude](./harp-materials.insertshaderinclude.md)

## insertShaderInclude() function

Insert shader includes after another shader include.

<b>Signature:</b>

```typescript
export declare function insertShaderInclude(shaderContent: string, shaderName: string, insertedShaderName: string, addTab?: boolean): string;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  shaderContent | string | Original string. |
|  shaderName | string | String to append to. |
|  insertedShaderName | string | String to append after string <code>shaderA</code>. |
|  addTab | boolean | If <code>true</code>, a tab character will be inserted before <code>shaderB</code>. |

<b>Returns:</b>

string
