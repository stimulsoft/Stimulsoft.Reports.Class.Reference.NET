---
title: "StiBookmark Class"
---

## StiBookmark Class

**Namespace:** `Stimulsoft.Report.Components`

The class describes a base bookmark class.

### Inheritance

Implements: [IStiJsonReportObject](../../Stimulsoft_Base/root/IStiJsonReportObject.md)  

### Constructors

| Constructor | Description |
| --- | --- |
| **StiBookmark**() | Creates a new bookmark. |
| **StiBookmark**(string text, object parentComponent) | Creates a new bookmark. |
| **StiBookmark**(string text, string bookmarkText, object parentComponent) | Creates a new bookmark. |

**StiBookmark**()

Creates a new bookmark.

---

**StiBookmark**(**text**: string, **parentComponent**: object)

Creates a new bookmark.

**Parameters**

- **text** (string) — Tree text.  
- **parentComponent** (object)  

---

**StiBookmark**(**text**: string, **bookmarkText**: string, **parentComponent**: object)

Creates a new bookmark.

**Parameters**

- **text** (string) — Tree text.  
- **bookmarkText** (string) — Boormark text.  
- **parentComponent** (object)  


### Properties

| Property | Type | Description |
| --- | --- | --- |
| **BookmarkText** | string |  |
| **ComponentGuid** | string |  |
| **Engine** | [StiEngineVersion](../../Stimulsoft_Base/Stimulsoft/Report/Engine/StiEngineVersion.md) |  |
| **IsManualBookmark** | bool |  |
| **PageIndex** | int |  |
| **ParentComponent** | object |  |
| **Text** | string |  |

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **Add** | void |  |
| **LoadFromJsonObject** | void |  |
| **SaveToJsonObject** | [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md) |  |

---

### Method Details

#### Add

**Add**(**name**: string): void

**Parameters**

- **name** (string)  


---

#### LoadFromJsonObject

**LoadFromJsonObject**(**jObject**: [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)): void

**Parameters**

- **jObject** ([JObject](../../Stimulsoft_Base/Json/Linq/JObject.md))  


---

#### SaveToJsonObject

**SaveToJsonObject**(**mode**: [StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md)): [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

**Parameters**

- **mode** ([StiJsonSaveMode](../../Stimulsoft_Base/root/StiJsonSaveMode.md))  

**Returns** [JObject](../../Stimulsoft_Base/Json/Linq/JObject.md)

