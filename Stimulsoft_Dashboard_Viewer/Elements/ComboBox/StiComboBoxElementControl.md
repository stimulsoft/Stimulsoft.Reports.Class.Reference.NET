---
title: "StiComboBoxElementControl Class"
---

## StiComboBoxElementControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Elements.ComboBox`

### Inheritance

Inherits from: StiFilterElementControl  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiComboBoxElementControl**(IStiElement element) |  |

**StiComboBoxElementControl**(**element**: IStiElement)

**Parameters**

- **element** (IStiElement)  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **IsAllItemsSelected** | bool |  |
| **OnSizeChanged** | void |  |
| **RefreshChild** | void |  |
| **RefreshChildControl** | void |  |
| **ResetFilter** | void |  |

---

### Method Details

#### IsAllItemsSelected

**IsAllItemsSelected**(): bool

**Returns** bool


---

#### OnSizeChanged

**OnSizeChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### RefreshChild

**RefreshChild**(**dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md)): void

**Parameters**

- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


---

#### RefreshChildControl

**RefreshChildControl**(****: StiComboBoxItemitems): void

**Parameters**

- **** (StiComboBoxItemitems)  


---

#### ResetFilter

**ResetFilter**(): void


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ComboBoxElement** | StiComboBoxElement |  |
| **MaxSelectedItems** | int |  |
| **ShowAllValue** | bool |  |
