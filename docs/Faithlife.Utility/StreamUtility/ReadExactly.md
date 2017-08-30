# StreamUtility.ReadExactly method (1 of 2)

Reads exactly *count* bytes from *stream*.

```csharp
public static byte[] ReadExactly(this Stream stream, int count)
```

| parameter | description |
| --- | --- |
| stream | The stream to read from. |
| count | The count of bytes to read. |

## Return Value

A new byte array containing the data read from the stream.

## See Also

* class [StreamUtility](../StreamUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# StreamUtility.ReadExactly method (2 of 2)

Reads exactly *count* bytes from *stream* into*buffer*, starting at the byte given by *offset*.

```csharp
public static void ReadExactly(this Stream stream, byte[] buffer, int offset, int count)
```

| parameter | description |
| --- | --- |
| stream | The stream to read from. |
| buffer | The buffer to read data into. |
| offset | The offset within the buffer at which data is first written. |
| count | The count of bytes to read. |

## See Also

* class [StreamUtility](../StreamUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->