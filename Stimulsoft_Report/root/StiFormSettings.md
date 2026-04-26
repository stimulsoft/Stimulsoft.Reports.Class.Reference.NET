---
title: "StiFormSettings Class"
---

## StiFormSettings Class

**Namespace:** `Stimulsoft.Report`

Class store information about form parameters.

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Load** `static` *(+1 overloads)* | void |  |
| **LoadSize** `static` | Size |  |
| **Save** `static` *(+1 overloads)* | void |  |

---

### Method Details

#### Load `static`

**Load**(**form**: Form, **skipLocation**: bool, **skipSize**: bool): void

**Parameters**

- **form** (Form)  
- **skipLocation** (bool)  
- **skipSize** (bool)  

---

**Load**(**name**: string, **form**: Form, **skipLocation**: bool, **skipSize**: bool): void

**Parameters**

- **name** (string)  
- **form** (Form)  
- **skipLocation** (bool)  
- **skipSize** (bool)  


---

#### LoadSize `static`

**LoadSize**(**form**: Form): Size

**Parameters**

- **form** (Form)  

**Returns** Size


---

#### Save `static`

**Save**(**form**: Form): void

**Parameters**

- **form** (Form)  

---

**Save**(**name**: string, **form**: Form): void

**Parameters**

- **name** (string)  
- **form** (Form)  

