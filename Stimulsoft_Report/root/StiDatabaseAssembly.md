---
title: "StiDatabaseAssembly Class"
---

## StiDatabaseAssembly Class

**Namespace:** `Stimulsoft.Report`

Internal use only.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **CanEditConnectionString** `static` | bool |  |
| **EditConnectionString** `static` | string |  |
| **GetAssembly** `static` | Assembly |  |
| **GetConnectionStringHelper** `static` | Type |  |
| **GetWpfConnectionStringHelper** `static` | Type |  |

---

### Method Details

#### CanEditConnectionString `static`

**CanEditConnectionString**(**typeName**: string): bool

**Parameters**

- **typeName** (string)  

**Returns** bool


---

#### EditConnectionString `static`

**EditConnectionString**(**database**: StiDatabase, **connectionString**: string, **typeName**: string): string

**Parameters**

- **database** (StiDatabase)  
- **connectionString** (string)  
- **typeName** (string)  

**Returns** string


---

#### GetAssembly `static`

**GetAssembly**(): Assembly

**Returns** Assembly


---

#### GetConnectionStringHelper `static`

**GetConnectionStringHelper**(**typeName**: string): Type

**Parameters**

- **typeName** (string)  

**Returns** Type


---

#### GetWpfConnectionStringHelper `static`

**GetWpfConnectionStringHelper**(**typeName**: string): Type

**Parameters**

- **typeName** (string)  

**Returns** Type

