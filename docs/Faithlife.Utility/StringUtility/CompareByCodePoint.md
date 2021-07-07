# StringUtility.CompareByCodePoint method

Compares two specified String objects by comparing successive Unicode code points. This method differs from String) in that this method considers supplementary characters (which are encoded as two surrogate code units) to be greater than characters in the base multilingual plane (because they have higher Unicode code points). This method sorts strings in code point order, which is the same as a byte-wise comparison of UTF-8 or UTF-32 encoded strings.

```csharp
public static int CompareByCodePoint(string? left, string? right)
```

| parameter | description |
| --- | --- |
| left | The first string. |
| right | The second string. |

## Return Value

Less than zero if *left* is less than *right*; zero if the strings are equal; greater than zero if *left* is greater than *right*.

## See Also

* class [StringUtility](../StringUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->