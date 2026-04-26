---
title: "StiPercentageFormatService Class"
---

## StiPercentageFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`

### Inheritance

Inherits from: [StiCurrencyFormatService](StiCurrencyFormatService.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiPercentageFormatService**() | Creates a new format of the type StiPercentageFormatService. |

**StiPercentageFormatService**()

Creates a new format of the type StiPercentageFormatService.


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateNew** | StiFormatService |  |
| **Equals** | bool |  |
| **Format** | string | Formats the specified object in order of regulations and returns a string. |
| **GetHashCode** | int |  |
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

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md)

