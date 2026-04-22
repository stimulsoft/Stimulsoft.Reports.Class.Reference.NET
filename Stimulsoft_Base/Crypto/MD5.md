---
title: "MD5 Class"
---

## MD5 Class

**Namespace:** `Stimulsoft.Base.Crypto`  
**Assembly:** `Stimulsoft.Base`

Implementation of MD5 as outlined in "Handbook of Applied Cryptography", pages 346 - 347.

```csharp
public class MD5
```

### Constructors

| Constructor | Description |
| --- | --- |
| **MD5**() | Creates a new instance |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **BlockUpdate** | void | Update hash by byte array |
| **GetHash** | byte[] | Get resulting hash |
| **Reset** | void | Reset the chaining variables to the initial values. |
| **Update** | void | Update hash by one byte |
