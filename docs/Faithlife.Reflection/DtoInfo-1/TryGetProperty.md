# DtoInfo&lt;T&gt;.TryGetProperty method (1 of 2)

Returns the property of the specified name.

```csharp
public IDtoProperty<T> TryGetProperty(string name)
```

| parameter | description |
| --- | --- |
| name | The property name. |

## Return Value

Returns `null` if the property does not exist.

## See Also

* interface [IDtoProperty&lt;T&gt;](../IDtoProperty-1.md)
* class [DtoInfo&lt;T&gt;](../DtoInfo-1.md)
* namespace [Faithlife.Reflection](../../Faithlife.Reflection.md)

---

# DtoInfo&lt;T&gt;.TryGetProperty&lt;TValue&gt; method (2 of 2)

Returns the property of the specified name.

```csharp
public DtoProperty<T, TValue> TryGetProperty<TValue>(string name)
```

| parameter | description |
| --- | --- |
| TValue | The value type of the property. |
| name | The property name. |

## Return Value

Returns `null` if the property does not exist.

## See Also

* class [DtoProperty&lt;TSource,TValue&gt;](../DtoProperty-2.md)
* class [DtoInfo&lt;T&gt;](../DtoInfo-1.md)
* namespace [Faithlife.Reflection](../../Faithlife.Reflection.md)

<!-- DO NOT EDIT: generated by xmldocmd for Faithlife.Reflection.dll -->
