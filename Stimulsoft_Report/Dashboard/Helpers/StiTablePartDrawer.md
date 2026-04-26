---
title: "StiTablePartDrawer Class"
---

## StiTablePartDrawer Class

**Namespace:** `Stimulsoft.Report.Dashboard.Helpers`

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTablePartDrawer**(DataGridViewCellPaintingEventArgs cellArgs, DataGridView grid) |  |

**StiTablePartDrawer**(**cellArgs**: DataGridViewCellPaintingEventArgs, **grid**: DataGridView)

**Parameters**

- **cellArgs** (DataGridViewCellPaintingEventArgs)  
- **grid** (DataGridView)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **DrawSimpleBorder** | bool |  |
| **WordWrapHeader** | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **DrawCell** | void |  |
| **DrawFilterArrow** | void |  |
| **DrawHeaderText** | void |  |
| **DrawSortArrow** | void |  |
| **DrawSortIndex** | void |  |
| **GetSortRectangle** *(+1 overloads)* | Rectangle |  |

---

### Method Details

#### DrawCell

**DrawCell**(): void


---

#### DrawFilterArrow

**DrawFilterArrow**(): void


---

#### DrawHeaderText

**DrawHeaderText**(): void


---

#### DrawSortArrow

**DrawSortArrow**(): void


---

#### DrawSortIndex

**DrawSortIndex**(**textRect**: Rectangle): void

**Parameters**

- **textRect** (Rectangle)  


---

#### GetSortRectangle

**GetSortRectangle**(**imageWidth**: int, **imageHeight**: int): Rectangle

**Parameters**

- **imageWidth** (int)  
- **imageHeight** (int)  

**Returns** Rectangle

---

**GetSortRectangle**(**cellBounds**: Rectangle): Rectangle

**Parameters**

- **cellBounds** (Rectangle)  

**Returns** Rectangle

