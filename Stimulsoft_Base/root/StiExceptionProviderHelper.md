---
title: "StiExceptionProviderHelper Class"
---

## StiExceptionProviderHelper Class

**Namespace:** `Stimulsoft.Base`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **ErrorBody** | string |  |
| **ErrorNumber** | string |  |
| **ErrorSubject** | string |  |
| **Ident** | string |  |
| **ResultSuccess** | bool |  |
| **UserName** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** | void |  |
| **SaveToString** | byte[] |  |
| **SendAsync** `static` | Task<bool> |  |

---

### Method Details

#### Load

**Load**(**str**: string): void

**Parameters**

- **str** (string)  


---

#### SaveToString

**SaveToString**(): byte[]

**Returns** byte[]


---

#### SendAsync `static`

**SendAsync**(**userName**: string, **errorSubject**: string, **errorBody**: string, **errorNumber**: string): Task<bool>

**Parameters**

- **userName** (string)  
- **errorSubject** (string)  
- **errorBody** (string)  
- **errorNumber** (string)  

**Returns** Task<bool>

