# IBrowserCache.SyncDbWithCacheAsync method

Calls the code to check save to/restore from cache.

```csharp
public Task<int> SyncDbWithCacheAsync(string filename)
```

| parameter | description |
| --- | --- |
| filename | The name of the file to process. |

## Return Value

Either -1 (no cache), 0 (restored), or 1 (cached).

## See Also

* interface [IBrowserCache](../IBrowserCache.md)
* namespace [SqliteWasmHelper](../../SqliteWasmHelper.md)

<!-- DO NOT EDIT: generated by xmldocmd for SqliteWasmHelper.dll -->