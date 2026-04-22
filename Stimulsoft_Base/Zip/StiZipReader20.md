---
title: "StiZipReader20 Class"
---

## StiZipReader20 Class

**Namespace:** `Stimulsoft.Base.Zip`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiZipReader20
```

### Inheritance

Implements: IDisposable  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiZipReader20**(string path) |  |
| **StiZipReader20**(Stream stream) |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clear** | void |  |
| **Close** *(+1 overloads)* | void |  |
| **ConvertToStringExt** `static` | string |  |
| **Dispose** | void |  |
| **Find** | bool |  |
| **Flush** *(+1 overloads)* | void |  |
| **GetEntryStream** | Stream |  |
| **Read** *(+1 overloads)* | int |  |
| **ReadByte** | int |  |
| **ReadFully** `static` *(+1 overloads)* | void |  |
| **ReadInt** | int |  |
| **ReadLEInt** | int |  |
| **ReadLELong** | long |  |
| **ReadLEShort** | int |  |
| **ReadLong** | long |  |
| **Seek** *(+1 overloads)* | long |  |
| **SetLength** *(+1 overloads)* | void |  |
| **Write** *(+1 overloads)* | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CentralHeaderSignature** | int |  |
| **EndOfCentralDirectorySignature** | int |  |
| **EndOfCentralRecordBaseSize** | int |  |
| **LocalHeaderBaseSize** | int |  |
| **LocalHeaderSignature** | int |  |
| **VersionMadeBy** | int |  |
| **VersionZip64** | int |  |
| **Zip64CentralDirLocatorSignature** | int |  |
| **Zip64CentralFileHeaderSignature** | int |  |
