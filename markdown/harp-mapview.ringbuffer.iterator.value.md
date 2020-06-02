<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@here/harp-mapview](./harp-mapview.md) &gt; [RingBuffer](./harp-mapview.ringbuffer.md) &gt; [Iterator](./harp-mapview.ringbuffer.iterator.md) &gt; [value](./harp-mapview.ringbuffer.iterator.value.md)

## RingBuffer.Iterator.value property

Gets the iterator's current value. This function does not fail even if an overrun occurs. To detect an overrun, watch the result for \[\[next\]\].

<b>Signature:</b>

```typescript
get value(): T;
```