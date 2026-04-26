---
title: "StiLocalizationExt Class"
---

## StiLocalizationExt Class

**Namespace:** `Stimulsoft.Report.Helper`

### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BlockLocalizationLoading** `static` | bool |  |
| **Localization** `static` | string | Gets or sets name of file with localized resource. |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Get** `static` *(+1 overloads)* | string |  |
| **GetValue** `static` | string |  |
| **Load** `static` *(+2 overloads)* | void |  |

---

### Method Details

#### Get `static`

**Get**(**category**: string, **key**: string): string

**Parameters**

- **category** (string)  
- **key** (string)  

**Returns** string

---

**Get**(**category**: string, **key**: string, **throwError**: bool): string

**Parameters**

- **category** (string)  
- **key** (string)  
- **throwError** (bool)  

**Returns** string


---

#### GetValue `static`

**GetValue**(**category**: string, **key**: string): string

**Parameters**

- **category** (string)  
- **key** (string)  

**Returns** string


---

#### Load `static`

**Load**(): void

---

**Load**(**file**: string): void

**Parameters**

- **file** (string)  

---

**Load**(**stream**: Stream): void

**Parameters**

- **stream** (Stream)  

