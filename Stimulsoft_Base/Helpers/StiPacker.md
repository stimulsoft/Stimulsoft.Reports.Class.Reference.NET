---
title: "StiPacker Class"
---

## StiPacker Class

**Namespace:** `Stimulsoft.Base.Helpers`  
**Assembly:** `Stimulsoft.Base`

This class helps in working with packing/unpacking data.

```csharp
public static class StiPacker
```

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowPacking** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IsPacked** `static` *(+1 overloads)* | bool | Returns true if the specified stream is packed. |
| **Pack** `static` *(+1 overloads)* | byte[] | Packs the byte array. |
| **PackAndEncrypt** `static` | byte[] | Packs and encrypts the byte array. |
| **PackAndEncryptToString** `static` | string | Packs and encrypts the byte array to the byte64 string. |
| **PackToBytes** `static` *(+1 overloads)* | byte[] | Packs string and convert it to byte array. |
| **PackToString** `static` | string |  |
| **Unpack** `static` *(+1 overloads)* | byte[] | Unpacks byte array. |
| **UnpackAndDecrypt** `static` *(+1 overloads)* | byte[] | Unpacks and uncrypts byte array. |
| **UnpackFromString** `static` | byte[] |  |
| **UnpackToString** `static` | string | Unpacks byte array and convert it to string. |
| **UnpackToXElement** `static` | XElement | Unpacks byte array and convert it to XElement. |
