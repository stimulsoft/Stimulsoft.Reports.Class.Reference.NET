---
title: "StiTableViewControl Class"
---

## StiTableViewControl Class

**Namespace:** `Stimulsoft.Dashboard.Viewer.Controls.Table`

### Inheritance

Inherits from: StiDataGridView  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTableViewControl**(StiTableElement element, [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md) dataTable) |  |

**StiTableViewControl**(**element**: StiTableElement, **dataTable**: [StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))

**Parameters**

- **element** (StiTableElement)  
- **dataTable** ([StiDataTable](../../../Stimulsoft_Data/Engine/StiDataTable.md))  


### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CreateAlternatingCellStyle** | DataGridViewCellStyle |  |
| **Dispose** | void |  |
| **GetColumnPath** | string |  |
| **GetInteraction** | [StiTableColumnDashboardInteraction](../../../Stimulsoft_Dashboard/Interactions/StiTableColumnDashboardInteraction.md) |  |
| **NewTab** | void |  |
| **OnCellMouseClick** | void |  |
| **OnCellMouseDown** | void |  |
| **OnCellMouseEnter** | void |  |
| **OnCellMouseLeave** | void |  |
| **OnCellMouseMove** | void |  |
| **OnCellMouseUp** | void |  |
| **OnCellPainting** | void |  |
| **OnDataSourceChanged** | void |  |
| **OnMouseLeave** | void |  |
| **OnMouseMove** | void |  |
| **OnPaintBackground** | void |  |

---

### Method Details

#### CreateAlternatingCellStyle

**CreateAlternatingCellStyle**(): DataGridViewCellStyle

**Returns** DataGridViewCellStyle


---

#### Dispose

**Dispose**(**disposing**: bool): void

**Parameters**

- **disposing** (bool)  


---

#### GetColumnPath

**GetColumnPath**(**tableColumn**: StiTableColumn): string

**Parameters**

- **tableColumn** (StiTableColumn)  

**Returns** string


---

#### GetInteraction

**GetInteraction**(**column**: StiTableColumn): [StiTableColumnDashboardInteraction](../../../Stimulsoft_Dashboard/Interactions/StiTableColumnDashboardInteraction.md)

**Parameters**

- **column** (StiTableColumn)  

**Returns** [StiTableColumnDashboardInteraction](../../../Stimulsoft_Dashboard/Interactions/StiTableColumnDashboardInteraction.md)


---

#### NewTab

**NewTab**(**page**: StiPage, **value**: string, **parameters**: List<DictionaryEntry>): void

**Parameters**

- **page** (StiPage)  
- **value** (string)  
- **parameters** (List<DictionaryEntry>)  


---

#### OnCellMouseClick

**OnCellMouseClick**(**e**: DataGridViewCellMouseEventArgs): void

**Parameters**

- **e** (DataGridViewCellMouseEventArgs)  


---

#### OnCellMouseDown

**OnCellMouseDown**(**e**: DataGridViewCellMouseEventArgs): void

**Parameters**

- **e** (DataGridViewCellMouseEventArgs)  


---

#### OnCellMouseEnter

**OnCellMouseEnter**(**e**: DataGridViewCellEventArgs): void

**Parameters**

- **e** (DataGridViewCellEventArgs)  


---

#### OnCellMouseLeave

**OnCellMouseLeave**(**e**: DataGridViewCellEventArgs): void

**Parameters**

- **e** (DataGridViewCellEventArgs)  


---

#### OnCellMouseMove

**OnCellMouseMove**(**e**: DataGridViewCellMouseEventArgs): void

**Parameters**

- **e** (DataGridViewCellMouseEventArgs)  


---

#### OnCellMouseUp

**OnCellMouseUp**(**e**: DataGridViewCellMouseEventArgs): void

**Parameters**

- **e** (DataGridViewCellMouseEventArgs)  


---

#### OnCellPainting

**OnCellPainting**(**e**: DataGridViewCellPaintingEventArgs): void

**Parameters**

- **e** (DataGridViewCellPaintingEventArgs)  


---

#### OnDataSourceChanged

**OnDataSourceChanged**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnMouseLeave

**OnMouseLeave**(**e**: EventArgs): void

**Parameters**

- **e** (EventArgs)  


---

#### OnMouseMove

**OnMouseMove**(**e**: MouseEventArgs): void

**Parameters**

- **e** (MouseEventArgs)  


---

#### OnPaintBackground

**OnPaintBackground**(**e**: PaintEventArgs): void

**Parameters**

- **e** (PaintEventArgs)  

