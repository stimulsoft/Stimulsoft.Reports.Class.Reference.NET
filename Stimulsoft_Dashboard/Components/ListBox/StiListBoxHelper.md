---
title: "StiListBoxHelper Class"
---

## StiListBoxHelper Class

**Namespace:** `Stimulsoft.Dashboard.Components.ListBox`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FetchDefaultUserFilters** `static` | List<StiDataFilterRule> |  |
| **FetchItems** `static` | [StiListBoxItem](StiListBoxItem.md)[] |  |
| **Format** `static` | string |  |
| **GetKeyMeterExpression** `static` | string |  |
| **GetKeyMeterIndex** `static` | int |  |
| **GetNameMeterIndex** `static` | int |  |
| **IsBlank** `static` | bool |  |

---

### Method Details

#### FetchDefaultUserFilters `static`

**FetchDefaultUserFilters**(**listBoxElement**: StiListBoxElement): List<StiDataFilterRule>

**Parameters**

- **listBoxElement** (StiListBoxElement)  

**Returns** List<StiDataFilterRule>


---

#### FetchItems `static`

**FetchItems**(**listBoxElement**: StiListBoxElement, **dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md), **showBlanks**: bool): [StiListBoxItem](StiListBoxItem.md)[]

**Parameters**

- **listBoxElement** (StiListBoxElement)  
- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **showBlanks** (bool)  

**Returns** [StiListBoxItem](StiListBoxItem.md)[]


---

#### Format `static`

**Format**(**listBoxElement**: StiListBoxElement, **value**: object): string

**Parameters**

- **listBoxElement** (StiListBoxElement)  
- **value** (object)  

**Returns** string


---

#### GetKeyMeterExpression `static`

**GetKeyMeterExpression**(**listBoxElement**: StiListBoxElement): string

**Parameters**

- **listBoxElement** (StiListBoxElement)  

**Returns** string


---

#### GetKeyMeterIndex `static`

**GetKeyMeterIndex**(**table**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **table** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### GetNameMeterIndex `static`

**GetNameMeterIndex**(**table**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): int

**Parameters**

- **table** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  

**Returns** int


---

#### IsBlank `static`

**IsBlank**(**data**: object): bool

**Parameters**

- **data** (object)  

**Returns** bool

