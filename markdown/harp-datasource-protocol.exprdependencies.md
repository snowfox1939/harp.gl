<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-datasource-protocol](./harp-datasource-protocol.md) &gt; [ExprDependencies](./harp-datasource-protocol.exprdependencies.md)

## ExprDependencies class

The dependencies of an \[\[Expr\]\].

<b>Signature:</b>

```typescript
export declare class ExprDependencies 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [featureState](./harp-datasource-protocol.exprdependencies.featurestate.md) |  | boolean | <code>true</code> if the expression depends on the feature state. |
|  [properties](./harp-datasource-protocol.exprdependencies.properties.md) |  | Set&lt;string&gt; | The properties needed to evaluate the \[\[Expr\]\]. |
|  [volatile](./harp-datasource-protocol.exprdependencies.volatile.md) |  | boolean | <code>true</code> if this expression cannot be cached. |
