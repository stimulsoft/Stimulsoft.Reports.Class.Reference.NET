---
title: "StiDataImages Class"
---

## StiDataImages Class

**Namespace:** `Stimulsoft.Report.Dictionary`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetImageFromColumn** `static` | [Image](../../Stimulsoft_Drawing/root/Image.md) |  |
| **GetImageKeyFromColumn** `static` | string |  |
| **GetImageKeyFromResource** `static` | string |  |
| **GetImageKeyFromVariable** `static` | string |  |

---

### Method Details

#### Get `static`

**Get**(**key**: string): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **key** (string)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetImageFromColumn `static`

**GetImageFromColumn**(**dataColumn**: StiDataColumn): [Image](../../Stimulsoft_Drawing/root/Image.md)

**Parameters**

- **dataColumn** (StiDataColumn)  

**Returns** [Image](../../Stimulsoft_Drawing/root/Image.md)


---

#### GetImageKeyFromColumn `static`

**GetImageKeyFromColumn**(**column**: StiDataColumn): string

**Parameters**

- **column** (StiDataColumn)  

**Returns** string


---

#### GetImageKeyFromResource `static`

**GetImageKeyFromResource**(**resource**: StiResource): string

**Parameters**

- **resource** (StiResource)  

**Returns** string


---

#### GetImageKeyFromVariable `static`

**GetImageKeyFromVariable**(**variable**: StiVariable): string

**Parameters**

- **variable** (StiVariable)  

**Returns** string


### Fields

| Field | Type | Description |
| --- | --- | --- |
| **ImageHeight** | int |  |
| **ImageWidth** | int |  |
| **Images** | ImageList |  |
