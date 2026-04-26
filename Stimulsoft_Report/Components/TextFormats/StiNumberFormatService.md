---
title: "StiNumberFormatService Class"
---

## StiNumberFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`

### Inheritance

Inherits from: StiFormatService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiNumberFormatService**() | Creates a new format of the type StiNumberFormatService. |

**StiNumberFormatService**()

Creates a new format of the type StiNumberFormatService.


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Clone** *(+1 overloads)* | object |  |
| **CorrectNegativeZero** | object |  |
| **CreateNew** | StiFormatService |  |
| **Equals** | bool |  |
| **Format** | string | Formats the specified object in order of regulations and returns a string. |
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

#### CorrectNegativeZero

**CorrectNegativeZero**(**arg**: object, **decimalDigits**: int): object

**Parameters**

- **arg** (object)  
- **decimalDigits** (int)  

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


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **decimalDigits** | int |  |
| **decimalSeparator** | string |  |
| **groupSeparator** | string |  |
| **groupSize** | int |  |
| **negativePattern** | int |  |
| **nullDisplay** | string |  |
| **states** | [StiTextFormatState](../../../Stimulsoft_Dashboard/root/StiTextFormatState.md) |  |
| **useGroupSeparator** | bool |  |
| **useLocalSetting** | bool |  |
