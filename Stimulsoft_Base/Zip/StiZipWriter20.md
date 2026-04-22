---
title: "StiZipWriter20 Class"
---

## StiZipWriter20 Class

**Namespace:** `Stimulsoft.Base.Zip`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiZipWriter20
```

### Constructors

| Constructor | Description |
| --- | --- |
| `StiZipWriter20()` |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **AddFile** *(+4 overloads)* | void |  |
| **Begin** | void |  |
| **Close** *(+1 overloads)* | void |  |
| **CloseEntry** | void | Close current entry |
| **End** | void |  |
| **Finish** *(+1 overloads)* | void |  |
| **Flush** | void |  |
| **PutNextEntry** | void | Put next entry into Zip file |
| **Read** | int |  |
| **ReadByte** | int |  |
| **Reset** | void |  |
| **Seek** | long |  |
| **SetLength** | void |  |
| **Write** *(+1 overloads)* | void |  |
| **WriteByte** | void |  |

### Fields

| Field | Type | Description |
| --- | --- | --- |
| **CentralHeaderBaseSize** | int |  |
| **CentralHeaderSignature** | int |  |
| **DataDescriptorSignature** | int |  |
| **DataDescriptorSize** | int |  |
| **DefaultEncoding** | Encoding |  |
| **EndOfCentralDirectorySignature** | int |  |
| **LocalHeaderBaseSize** | int |  |
| **LocalHeaderSignature** | int |  |
| **TotalOut** | int |  |
| **Version** | int |  |
| **baseOutputStream** | Stream |  |
