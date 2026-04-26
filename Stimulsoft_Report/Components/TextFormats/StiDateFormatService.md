---
title: "StiDateFormatService Class"
---

## StiDateFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`

### Inheritance

Inherits from: StiFormatService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiDateFormatService**() | Creates a new format of the type StiDateFormatService. |

**StiDateFormatService**()

Creates a new format of the type StiDateFormatService.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **NullDisplay** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateNew** | StiFormatService |  |
| **Equals** | bool |  |
| **Format** | string | Formats the specified object in order of regulations and returns a string. |
| **GetHashCode** | int |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### CreateNew

**CreateNew**(): StiFormatService

**Returns** StiFormatService


---

#### Equals

**Equals**(**obj**: object): bool

**Parameters**

- **obj** (object)  

**Returns** bool


---

#### Format

**Format**(**stringFormat**: string, **arg**: object): string

Formats the specified object in order of regulations and returns a string.

**Parameters**

- **stringFormat** (string) — String for formatting.  
- **arg** (object) — Object for formatting.  

**Returns** string — Formatted string.


---

#### GetHashCode

**GetHashCode**(): int

**Returns** int


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

