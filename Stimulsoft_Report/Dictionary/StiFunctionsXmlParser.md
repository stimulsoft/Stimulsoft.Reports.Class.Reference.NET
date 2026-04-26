---
title: "StiFunctionsXmlParser Class"
---

## StiFunctionsXmlParser Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadDefaultFunctions** `static` | void |  |
| **LoadFunctionsFromXml** `static` *(+3 overloads)* | void |  |
| **TryLoadDefaultFunctions** `static` | bool |  |

---

### Method Details

#### LoadDefaultFunctions `static`

**LoadDefaultFunctions**(): void


---

#### LoadFunctionsFromXml `static`

**LoadFunctionsFromXml**(**assembly**: Assembly, ****: stringresourceNames): void

**Parameters**

- **assembly** (Assembly)  
- **** (stringresourceNames)  

---

**LoadFunctionsFromXml**(**assembly**: Assembly, **resourceName**: string): void

**Parameters**

- **assembly** (Assembly)  
- **resourceName** (string)  

---

**LoadFunctionsFromXml**(**fileName**: string): void

**Parameters**

- **fileName** (string)  

---

**LoadFunctionsFromXml**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  


---

#### TryLoadDefaultFunctions `static`

**TryLoadDefaultFunctions**(): bool

**Returns** bool

