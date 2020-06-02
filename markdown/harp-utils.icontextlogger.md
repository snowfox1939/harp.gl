<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-utils](./harp-utils.md) &gt; [IContextLogger](./harp-utils.icontextlogger.md)

## IContextLogger interface

Extension of \[\[ISimpleChannel\]\] to support contextual logging by adding stack of prefixes.

<b>Signature:</b>

```typescript
export interface IContextLogger extends ISimpleChannel 
```

## Methods

|  Method | Description |
|  --- | --- |
|  [pop()](./harp-utils.icontextlogger.pop.md) | Remove current context from top of stack. |
|  [pushAttr(name)](./harp-utils.icontextlogger.pushattr.md) | Push "attribute-like" context. |
|  [pushIndex(index)](./harp-utils.icontextlogger.pushindex.md) | Push "index-like" context.<!-- -->Following log messages will be prefixed with <code>[index]</code>. |
