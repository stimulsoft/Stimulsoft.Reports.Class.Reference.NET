---
title: "StiComboBoxHelper Class"
---

## StiComboBoxHelper Class

**Namespace:** `Stimulsoft.Dashboard.Components.ComboBox`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **FetchDefaultUserFilters** `static` | List<StiDataFilterRule> |  |
| **FetchItems** `static` | [StiComboBoxItem](StiComboBoxItem.md)[] |  |
| **GetKeyMeterExpression** `static` | string |  |
| **IsBlank** `static` | bool |  |

---

### Method Details

#### FetchDefaultUserFilters `static`

**FetchDefaultUserFilters**(**comboBoxElement**: StiComboBoxElement): List<StiDataFilterRule>

**Parameters**

- **comboBoxElement** (StiComboBoxElement)  

**Returns** List<StiDataFilterRule>


---

#### FetchItems `static`

**FetchItems**(**comboBoxElement**: StiComboBoxElement, **dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md), **showBlanks**: bool): [StiComboBoxItem](StiComboBoxItem.md)[]

**Parameters**

- **comboBoxElement** (StiComboBoxElement)  
- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  
- **showBlanks** (bool)  

**Returns** [StiComboBoxItem](StiComboBoxItem.md)[]


---

#### GetKeyMeterExpression `static`

**GetKeyMeterExpression**(**comboBoxElement**: StiComboBoxElement): string

**Parameters**

- **comboBoxElement** (StiComboBoxElement)  

**Returns** string


---

#### IsBlank `static`

**IsBlank**(**data**: object): bool

**Parameters**

- **data** (object)  

**Returns** bool

