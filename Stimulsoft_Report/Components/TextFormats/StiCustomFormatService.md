---
title: "StiCustomFormatService Class"
---

## StiCustomFormatService Class

**Namespace:** `Stimulsoft.Report.Components.TextFormats`

### Inheritance

Inherits from: StiFormatService  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiCustomFormatService**() | Creates a new format of the type StiCustomFormatService. |
| **StiCustomFormatService**(string stringFormat) | Creates a new format of the type StiCustomFormatService. |

**StiCustomFormatService**()

Creates a new format of the type StiCustomFormatService.

---

**StiCustomFormatService**(**stringFormat**: string)

Creates a new format of the type StiCustomFormatService.

**Parameters**

- **stringFormat** (string) — String of formatting  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateNew** | StiFormatService |  |
| **Equals** | bool |  |
| **Format** | string | Formats the specified object in order of regulations and returns a string. |
| **GetHashCode** | int |  |

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

