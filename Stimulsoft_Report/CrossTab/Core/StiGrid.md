---
title: "StiGrid Class"
---

## StiGrid Class

**Namespace:** `Stimulsoft.Report.CrossTab.Core`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Cells** | StiCell[][] |  |
| **CoordX** | decimal[] |  |
| **CoordY** | decimal[] |  |
| **DesignTime** | bool |  |
| **Fields** | Hashtable |  |
| **Heights** | decimal[] |  |
| **MaxHeight** | decimal |  |
| **MaxWidth** | decimal |  |
| **Report** | [StiReport](../../root/StiReport.md) |  |
| **Widths** | decimal[] |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DoAutoSize** | void |  |
| **HasRightCrossTitle** | bool |  |
| **Init** | void |  |
| **SetCellField** | void |  |
| **SetTextOfCell** | void |  |

---

### Method Details

#### DoAutoSize

**DoAutoSize**(): void


---

#### HasRightCrossTitle

**HasRightCrossTitle**(): bool

**Returns** bool


---

#### Init

**Init**(**colCount**: int, **rowCount**: int): void

**Parameters**

- **colCount** (int)  
- **rowCount** (int)  


---

#### SetCellField

**SetCellField**(**cellX**: int, **cellY**: int, **field**: StiCrossField): void

**Parameters**

- **cellX** (int)  
- **cellY** (int)  
- **field** (StiCrossField)  


---

#### SetTextOfCell

**SetTextOfCell**(**x**: int, **y**: int, **value**: string): void

**Parameters**

- **x** (int)  
- **y** (int)  
- **value** (string)  


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **AlignToGrid** | bool |  |
