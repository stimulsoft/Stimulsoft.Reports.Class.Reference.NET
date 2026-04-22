---
title: "StiCID Class"
---

## StiCID Class

**Namespace:** `Stimulsoft.Base`  
**Assembly:** `Stimulsoft.Base`

```csharp
public class StiCID
```

### Inheritance

Inherits from: [StiObject](StiObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCID**(string cid) |  |
| **StiCID**(string machineName, string machineAddress, string machineUserName) |  |
| **StiCID**(string machineName, string machineAddress, string machineUserName, string machineGuid) |  |

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **MachineAddress** | string |  |
| **MachineGuid** | string |  |
| **MachineName** | string |  |
| **MachineUserName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDefault** `static` | string |  |
| **GetDefaultAsync** `static` | Task<string> |  |
| **IsCID** `static` | bool |  |
