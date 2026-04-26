---
title: "StiCID Class"
---

## StiCID Class

**Namespace:** `Stimulsoft.Base`

### Inheritance

Inherits from: [StiObject](StiObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCID**(string cid) |  |
| **StiCID**(string machineName, string machineAddress, string machineUserName) |  |
| **StiCID**(string machineName, string machineAddress, string machineUserName, string machineGuid) |  |

**StiCID**(**cid**: string)

**Parameters**

- **cid** (string)  

---

**StiCID**(**machineName**: string, **machineAddress**: string, **machineUserName**: string)

**Parameters**

- **machineName** (string)  
- **machineAddress** (string)  
- **machineUserName** (string)  

---

**StiCID**(**machineName**: string, **machineAddress**: string, **machineUserName**: string, **machineGuid**: string)

**Parameters**

- **machineName** (string)  
- **machineAddress** (string)  
- **machineUserName** (string)  
- **machineGuid** (string)  


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

---

### Method Details

#### GetDefault `static`

**GetDefault**(): string

**Returns** string


---

#### GetDefaultAsync `static`

**GetDefaultAsync**(): Task<string>

**Returns** Task<string>


---

#### IsCID `static`

**IsCID**(**cid**: string): bool

**Parameters**

- **cid** (string)  

**Returns** bool

