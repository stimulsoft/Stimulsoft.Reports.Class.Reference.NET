---
title: "StiBusinessObjectData Class"
---

## StiBusinessObjectData Class

**Namespace:** `Stimulsoft.Report.Dictionary`

Class which contains information about business object which registered in report.

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBusinessObjectData**(string category, string name, object value) | Creates new instance of StiBusinessObject class. |
| **StiBusinessObjectData**(string category, string name, string alias, object value) | Creates new instance of StiBusinessObject class. |

**StiBusinessObjectData**(**category**: string, **name**: string, **value**: object)

Creates new instance of StiBusinessObject class.

**Parameters**

- **category** (string) — Category of business object.  
- **name** (string) — Name of business object.  
- **value** (object) — Business object.  

---

**StiBusinessObjectData**(**category**: string, **name**: string, **alias**: string, **value**: object)

Creates new instance of StiBusinessObject class.

**Parameters**

- **category** (string) — Category of business object.  
- **name** (string) — Name of business object.  
- **alias** (string) — Alias of business object.  
- **value** (object) — Business object.  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **Alias** | string | Gets or sets alias of business object. |
| **BusinessObjectValue** | object | Gets or sets business object. |
| **Category** | string | Gets or sets category name of business object. |
| **Name** | string | Gets or sets name of business object. |
