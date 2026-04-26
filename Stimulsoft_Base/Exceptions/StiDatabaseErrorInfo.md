---
title: "StiDatabaseErrorInfo Class"
---

## StiDatabaseErrorInfo Class

**Namespace:** `Stimulsoft.Base.Exceptions`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Category** | [StiDatabaseErrorCategory](StiDatabaseErrorCategory.md) |  |
| **Database** | string |  |
| **ErrorCode** | string |  |
| **Hint** | string |  |
| **IsTransient** | bool |  |
| **Message** | string |  |
| **Object** | string |  |
| **Raw** | Exception |  |
| **Schema** | string |  |
| **Server** | string |  |
| **SqlState** | string |  |
| **Subcategory** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **GetMessage** | string |  |
| **Unknown** `static` | [StiDatabaseErrorInfo](StiDatabaseErrorInfo.md) |  |

---

### Method Details

#### GetMessage

**GetMessage**(): string

**Returns** string


---

#### Unknown `static`

**Unknown**(**ex**: Exception, **hint**: string): [StiDatabaseErrorInfo](StiDatabaseErrorInfo.md)

**Parameters**

- **ex** (Exception)  
- **hint** (string)  

**Returns** [StiDatabaseErrorInfo](StiDatabaseErrorInfo.md)

