---
title: "StiCurrencyFormatService Class"
---

## StiCurrencyFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`

### Inheritance

Inherits from: [StiNumberFormatService](StiNumberFormatService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCurrencyFormatService**() | Creates a new format of the type StiCurrencyFormatService. |

**StiCurrencyFormatService**()

Creates a new format of the type StiCurrencyFormatService.


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **PositivePattern** | int |  |
| **Symbol** | string |  |

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

- **stringFormat** (string) — String of formatting.  
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

