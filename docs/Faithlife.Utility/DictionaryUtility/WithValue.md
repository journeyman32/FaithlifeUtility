# DictionaryUtility.WithValue&lt;TKey,TValue&gt; method (1 of 2)

Tries to get a value from the dictionary, executing the specified action if it exists.

```csharp
public static void WithValue<TKey, TValue>(this IDictionary<TKey, TValue> dict, TKey key, Action<TValue> fn)
```

| parameter | description |
| --- | --- |
| TKey | The type of the key. |
| TValue | The type of the value. |
| dict | The dictionary. |
| key | The key. |
| fn | The action. |

## See Also

* class [DictionaryUtility](../DictionaryUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

---

# DictionaryUtility.WithValue&lt;TKey,TValue,TResult&gt; method (2 of 2)

Tries to get a value from the dictionary, executing the specified action if it exists.

```csharp
public static TResult WithValue<TKey, TValue, TResult>(this IDictionary<TKey, TValue> dict, TKey key, Func<TValue, TResult> fn)
```

| parameter | description |
| --- | --- |
| TKey | The type of the key. |
| TValue | The type of the value. |
| TResult | The type of the result. |
| dict | The dictionary. |
| key | The key. |
| fn | The action. |

## See Also

* class [DictionaryUtility](../DictionaryUtility.md)
* namespace [Faithlife.Utility](../../Faithlife.Utility.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Utility.dll -->