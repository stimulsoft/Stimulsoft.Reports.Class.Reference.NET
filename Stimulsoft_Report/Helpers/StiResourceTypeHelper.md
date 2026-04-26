---
title: "StiResourceTypeHelper Class"
---

## StiResourceTypeHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetDataSourceIconName** `static` | string |  |
| **GetExtension** `static` | string |  |
| **GetFilter** `static` | string |  |
| **GetResourceFileName** `static` | string |  |
| **GetResourceImage** `static` | [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md) |  |
| **GetTypeFromExtension** `static` | StiResourceType? |  |
| **IsImageType** `static` | bool |  |
| **IsPossibleToConvertToDataSource** `static` | bool |  |
| **IsTextType** `static` | bool |  |

---

### Method Details

#### GetDataSourceIconName `static`

**GetDataSourceIconName**(**type**: [StiResourceType](../Dictionary/StiResourceType.md)): string

**Parameters**

- **type** ([StiResourceType](../Dictionary/StiResourceType.md))  

**Returns** string


---

#### GetExtension `static`

**GetExtension**(**type**: [StiResourceType](../Dictionary/StiResourceType.md)): string

**Parameters**

- **type** ([StiResourceType](../Dictionary/StiResourceType.md))  

**Returns** string


---

#### GetFilter `static`

**GetFilter**(**type**: [StiResourceType](../Dictionary/StiResourceType.md)): string

**Parameters**

- **type** ([StiResourceType](../Dictionary/StiResourceType.md))  

**Returns** string


---

#### GetResourceFileName `static`

**GetResourceFileName**(**resource**: StiResource): string

**Parameters**

- **resource** (StiResource)  

**Returns** string


---

#### GetResourceImage `static`

**GetResourceImage**(**resource**: StiResource): [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)

**Parameters**

- **resource** (StiResource)  

**Returns** [Bitmap](../../Stimulsoft_Drawing/root/Bitmap.md)


---

#### GetTypeFromExtension `static`

**GetTypeFromExtension**(**extension**: string): StiResourceType?

**Parameters**

- **extension** (string)  

**Returns** StiResourceType?


---

#### IsImageType `static`

**IsImageType**(**ext**: string): bool

**Parameters**

- **ext** (string)  

**Returns** bool


---

#### IsPossibleToConvertToDataSource `static`

**IsPossibleToConvertToDataSource**(**type**: [StiResourceType](../Dictionary/StiResourceType.md)): bool

**Parameters**

- **type** ([StiResourceType](../Dictionary/StiResourceType.md))  

**Returns** bool


---

#### IsTextType `static`

**IsTextType**(**ext**: string): bool

**Parameters**

- **ext** (string)  

**Returns** bool

