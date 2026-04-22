---
title: "StiKeyHelper Class"
---

## StiKeyHelper Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

This class helps work with keys.

```csharp
public static class StiKeyHelper
```

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GenerateKey** `static` | string | Returns new generated key. |
| **GetOrGeneratedKey** `static` *(+1 overloads)* | string | Returns specified key if it is not empty. Otherwise returns new generated key. |
| **IsCorrectKey** `static` | bool | Returns true if the specified key is correct. |
| **IsEmptyKey** `static` *(+1 overloads)* | bool | Returns true if the specifeid key is empty. |
| **IsEqualKeys** `static` | bool | Returns true if both keys equals. |
| **IsKey** `static` | bool | Returns true if the specified key is not empty. |
| **SelectKey** `static` | string | Returns key1 if it is not empty. Otherwise returns key2. |
