# EnumerableUtility.WhereNotNull&lt;T&gt; method (1 of 2)

Enumerates the specified collection, returning all the elements that are not null.

```csharp
public static IEnumerable<T> WhereNotNull<T>(this IEnumerable<T?> source)
    where T : class
```

| parameter | description |
| --- | --- |
| source | The sequence to enumerate. |

## Return Value

The non null items.

## See Also

* class [EnumerableUtility](../EnumerableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# EnumerableUtility.WhereNotNull&lt;T&gt; method (2 of 2)

Enumerates the specified collection, returning all the elements that are not null.

```csharp
public static IEnumerable<T> WhereNotNull<T>(this IEnumerable<T?> source)
    where T : struct
```

| parameter | description |
| --- | --- |
| source | The sequence to enumerate. |

## Return Value

The non null items.

## See Also

* class [EnumerableUtility](../EnumerableUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->