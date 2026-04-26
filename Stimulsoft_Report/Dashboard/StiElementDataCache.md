---
title: "StiElementDataCache Class"
---

## StiElementDataCache Class

**Namespace:** `Stimulsoft.Report.Dashboard`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **AllowParallelCalculations** `static` | bool |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CleanCache** `static` | void |  |
| **Create** `static` | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Get** `static` | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **GetKey** `static` | string |  |
| **GetOrCreate** `static` | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |
| **Remove** `static` | void |  |
| **TryToGetOrCreate** `static` | [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md) |  |

---

### Method Details

#### CleanCache `static`

**CleanCache**(**reportKey**: string): void

**Parameters**

- **reportKey** (string)  


---

#### Create `static`

**Create**(**element**: IStiElement, **dataRequestOption**: [StiDataRequestOption](../../Stimulsoft_Data/Engine/StiDataRequestOption.md)): [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)

**Parameters**

- **element** (IStiElement)  
- **dataRequestOption** ([StiDataRequestOption](../../Stimulsoft_Data/Engine/StiDataRequestOption.md))  

**Returns** [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)


---

#### Get `static`

**Get**(**element**: IStiElement): [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)

**Parameters**

- **element** (IStiElement)  

**Returns** [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)


---

#### GetKey `static`

**GetKey**(**element**: IStiElement): string

**Parameters**

- **element** (IStiElement)  

**Returns** string


---

#### GetOrCreate `static`

**GetOrCreate**(**element**: IStiElement, **option**: [StiDataRequestOption](../../Stimulsoft_Data/Engine/StiDataRequestOption.md)): [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)

**Parameters**

- **element** (IStiElement)  
- **option** ([StiDataRequestOption](../../Stimulsoft_Data/Engine/StiDataRequestOption.md))  

**Returns** [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)


---

#### Remove `static`

**Remove**(**key**: string): void

**Parameters**

- **key** (string)  


---

#### TryToGetOrCreate `static`

**TryToGetOrCreate**(**element**: IStiElement, **option**: [StiDataRequestOption](../../Stimulsoft_Data/Engine/StiDataRequestOption.md)): [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)

**Parameters**

- **element** (IStiElement)  
- **option** ([StiDataRequestOption](../../Stimulsoft_Data/Engine/StiDataRequestOption.md))  

**Returns** [StiDataTable](../../Stimulsoft_Data/Engine/StiDataTable.md)


### Events

| Event | Type | Description |
| --- | --- | --- |
| **DataInit** | EventHandler |  |
