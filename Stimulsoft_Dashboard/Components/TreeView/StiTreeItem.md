---
title: "StiTreeItem Class"
---

## StiTreeItem Class

**Namespace:** `Stimulsoft.Dashboard.Components.TreeView`

Describes base information about tree-view items.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiTreeItem**() |  |
| **StiTreeItem**(object key) |  |
| **StiTreeItem**(object key, [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md) meter) |  |

**StiTreeItem**()

---

**StiTreeItem**(**key**: object)

**Parameters**

- **key** (object)  

---

**StiTreeItem**(**key**: object, **meter**: [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md))

**Parameters**

- **key** (object)  
- **meter** ([IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md))  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Items** | List<[StiTreeItem](StiTreeItem.md)> | Nested items of this item. |
| **Key** | object | A unique key of a tree-view item. |
| **Meter** | [IStiMeter](../../../Stimulsoft_Base/Meters/IStiMeter.md) | A related meter object. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ToString** | string |  |

---

### Method Details

#### ToString

**ToString**(): string

**Returns** string

