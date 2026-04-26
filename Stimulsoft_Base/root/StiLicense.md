---
title: "StiLicense Class"
---

## StiLicense Class

**Namespace:** `Stimulsoft.Base`

This class is used for setup licensing of the reporting tool.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **LoadFromAssembly** `static` | void |  |
| **LoadFromEntryAssembly** `static` | void |  |
| **LoadFromFile** `static` | void | Loads a license key from the specified file. |
| **LoadFromStream** `static` | void | Loads a license key from the specified stream. |
| **LoadFromString** `static` | void | Loads a license key from the specified string. |

---

### Method Details

#### LoadFromAssembly `static`

**LoadFromAssembly**(**a**: Assembly, **resourceName**: string): void

**Parameters**

- **a** (Assembly)  
- **resourceName** (string)  


---

#### LoadFromEntryAssembly `static`

**LoadFromEntryAssembly**(**resourceName**: string): void

**Parameters**

- **resourceName** (string)  


---

#### LoadFromFile `static`

**LoadFromFile**(**file**: string): void

Loads a license key from the specified file.

**Parameters**

- **file** (string)  


---

#### LoadFromStream `static`

**LoadFromStream**(**stream**: Stream): void

Loads a license key from the specified stream.

**Parameters**

- **stream** (Stream)  


---

#### LoadFromString `static`

**LoadFromString**(**licenseKey**: string): void

Loads a license key from the specified string.

**Parameters**

- **licenseKey** (string)  

