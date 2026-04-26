---
title: "StiExportSettingsList Class"
---

## StiExportSettingsList Class

**Namespace:** `Stimulsoft.Report.Export`

### Inheritance

Inherits from: List<[StiExportSettings](StiExportSettings.md)>  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ContainsService** | bool |  |
| **IsEqualExport** `static` *(+1 overloads)* | bool |  |
| **LoadFromFile** | void |  |
| **LoadFromString** | void |  |
| **SaveToFile** | void |  |
| **SaveToString** | string |  |

---

### Method Details

#### ContainsService

**ContainsService**(**service**: [StiExportService](StiExportService.md)): bool

**Parameters**

- **service** ([StiExportService](StiExportService.md))  

**Returns** bool


---

#### IsEqualExport `static`

**IsEqualExport**(**c**: [StiExportSettings](StiExportSettings.md), **service**: [StiExportService](StiExportService.md)): bool

**Parameters**

- **c** ([StiExportSettings](StiExportSettings.md))  
- **service** ([StiExportService](StiExportService.md))  

**Returns** bool

---

**IsEqualExport**(**c**: [StiExportSettings](StiExportSettings.md), **s**: [StiExportSettings](StiExportSettings.md)): bool

**Parameters**

- **c** ([StiExportSettings](StiExportSettings.md))  
- **s** ([StiExportSettings](StiExportSettings.md))  

**Returns** bool


---

#### LoadFromFile

**LoadFromFile**(**file**: string): void

**Parameters**

- **file** (string)  


---

#### LoadFromString

**LoadFromString**(**str**: string): void

**Parameters**

- **str** (string)  


---

#### SaveToFile

**SaveToFile**(**file**: string): void

**Parameters**

- **file** (string)  


---

#### SaveToString

**SaveToString**(): string

**Returns** string

