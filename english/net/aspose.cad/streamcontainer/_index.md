---
title: Class StreamContainer
second_title: Aspose.CAD for .NET API Reference
description: Aspose.CAD.StreamContainer class. Represents stream container which contains the stream and provides stream processing routines
type: docs
weight: 36980
url: /net/aspose.cad/streamcontainer/
---
## StreamContainer class

Represents stream container which contains the stream and provides stream processing routines.

```csharp
public class StreamContainer : DisposableObject
```

## Constructors

| Name | Description |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Initializes a new instance of the `StreamContainer` class. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Initializes a new instance of the `StreamContainer` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [CanRead](../../aspose.cad/streamcontainer/canread/) { get; } | Gets a value indicating whether stream supports reading. |
| virtual [CanSeek](../../aspose.cad/streamcontainer/canseek/) { get; } | Gets a value indicating whether stream supports seeking. |
| virtual [CanWrite](../../aspose.cad/streamcontainer/canwrite/) { get; } | Gets a value indicating whether stream supports writing. |
| [Disposed](../../aspose.cad/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [IsStreamDisposedOnClose](../../aspose.cad/streamcontainer/isstreamdisposedonclose/) { get; } | Gets a value indicating whether this stream is disposed on close. |
| virtual [Length](../../aspose.cad/streamcontainer/length/) { get; set; } | Gets or sets the stream length in bytes. This value is less than the Length by the starting stream position passed in the StreamContainer constructor. |
| virtual [Position](../../aspose.cad/streamcontainer/position/) { get; set; } | Gets or sets the current position within the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [Stream](../../aspose.cad/streamcontainer/stream/) { get; } | Gets the data stream. |
| [SyncRoot](../../aspose.cad/streamcontainer/syncroot/) { get; } | Gets an object that can be used to synchronize access to the synchronized resource. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.cad/disposableobject/dispose/)() | Disposes the current instance. |
| virtual [Flush](../../aspose.cad/streamcontainer/flush/)() | Clears all buffers for this stream and causes any buffered data to be written to the underlying device. |
| virtual [Read](../../aspose.cad/streamcontainer/read/#read)(byte[]) | Reads bytes to fill the specified bytes buffer. |
| virtual [Read](../../aspose.cad/streamcontainer/read/#read_1)(byte[], int, int) | Reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read. |
| virtual [ReadByte](../../aspose.cad/streamcontainer/readbyte/)() | Reads a byte from the stream and advances the position within the stream by one byte, or returns -1 if at the end of the stream. |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save)(Stream) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](./readwritebytescount/) and stream [`Length`](./length/) value. |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_3)(string) | Saves (copies) the stream's data to the specified stream. Uses default buffer size [`ReadWriteBytesCount`](./readwritebytescount/) and stream [`Length`](./length/) value. |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_1)(Stream, int) | Saves (copies) all the stream's data to the specified stream. Uses stream [`Length`](./length/) value. |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_4)(string, int) | Saves (copies) the stream's data to the specified stream. Uses stream [`Length`](./length/) value. |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_2)(Stream, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Save](../../aspose.cad/streamcontainer/save/#save_5)(string, int, long) | Saves (copies) the stream's data to the specified stream. |
| virtual [Seek](../../aspose.cad/streamcontainer/seek/)(long, SeekOrigin) | Sets the position within the current stream. |
| virtual [SeekBegin](../../aspose.cad/streamcontainer/seekbegin/)() | Sets the stream position to the beginning of the stream. This value represents offset from the starting stream position passed in the StreamContainer constructor. |
| virtual [ToBytes](../../aspose.cad/streamcontainer/tobytes/#tobytes)() | Converts the stream data to the Byte array. |
| virtual [ToBytes](../../aspose.cad/streamcontainer/tobytes/#tobytes_1)(long, long) | Converts the stream data to the Byte array. |
| virtual [Write](../../aspose.cad/streamcontainer/write/#write)(byte[]) | Writes all of the specified bytes to the stream. |
| virtual [Write](../../aspose.cad/streamcontainer/write/#write_1)(byte[], int, int) | Writes a sequence of bytes to the current stream and advances the current position within this stream by the number of bytes written. |
| virtual [WriteByte](../../aspose.cad/streamcontainer/writebyte/)(byte) | Writes a byte to the current position in the stream and advances the position within the stream by one byte. |
| virtual [WriteTo](../../aspose.cad/streamcontainer/writeto/#writeto)(StreamContainer) | Copies the contained data to another `StreamContainer`. |
| virtual [WriteTo](../../aspose.cad/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Copies the contained data to another `StreamContainer`. |
| [explicit operator](../../aspose.cad/streamcontainer/op_explicit/) | Performs an explicit conversion from `StreamContainer` to Stream. |

## Fields

| Name | Description |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.cad/streamcontainer/readwritebytescount/) | Specifies read and write bytes count when reading sequentially. |

### See Also

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.CAD](../../aspose.cad/)
* assembly [Aspose.CAD](../../)

