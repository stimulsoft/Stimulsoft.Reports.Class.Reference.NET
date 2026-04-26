---
title: "StiBooleanFormatService Class"
---

## StiBooleanFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`

### Inheritance

Inherits from: StiFormatService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBooleanFormatService**() | Creates a new format of the type StiBooleanFormatService. |

**StiBooleanFormatService**()

Creates a new format of the type StiBooleanFormatService.


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** *(+1 overloads)* | object |  |
| **CreateNew** | StiFormatService |  |
| **Equals** | bool |  |
| **Format** | string | Formats the specified object on specified rule and returns the line. |
| **GetHashCode** | int |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Clone

**Clone**(): object

**Returns** object

---

**Clone**(): object

**Returns** object


---

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

Formats the specified object on specified rule and returns the line.

**Parameters**

- **stringFormat** (string) — String of the formatting.  
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


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **falseDisplay** | string |  |
| **falseValue** | string |  |
| **nullDisplay** | string |  |
| **trueDisplay** | string |  |
| **trueValue** | string |  |
