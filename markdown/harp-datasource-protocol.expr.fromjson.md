<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [Expr](./harp-datasource-protocol.expr.md) &gt; [fromJSON](./harp-datasource-protocol.expr.fromjson.md)

## Expr.fromJSON() method

Parse expression in JSON form.

If `definitions` are defined, then references (`['ref', name]`<!-- -->) are resolved.

Pass `definitionExprCache` to reuse `Expr` instances created from definitions across many `fromJSON` calls.

<b>Signature:</b>

```typescript
static fromJSON(node: JsonValue, definitions?: Definitions, definitionExprCache?: Map<string, Expr>): Expr;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  node | [JsonValue](./harp-datasource-protocol.jsonvalue.md) | expression in JSON format to parse |
|  definitions | [Definitions](./harp-datasource-protocol.definitions.md) | optional set of definitions needed definition resolved by <code>ref</code> operator |
|  definitionExprCache | Map&lt;string, [Expr](./harp-datasource-protocol.expr.md)<!-- -->&gt; | optional cache of <code>Expr</code> instances derived from <code>definitions</code> |

<b>Returns:</b>

[Expr](./harp-datasource-protocol.expr.md)
