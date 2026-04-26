---
title: "StiMapKeyHelper Class"
---

## StiMapKeyHelper Class

**Namespace:** `Stimulsoft.Report.Helpers`

### Inheritance

Implements: [IStiMapKeyHelper](../../Stimulsoft_Base/Map/IStiMapKeyHelper.md)  

### Methods

| Method | Returns | Description |
| --- | --- | --- |
| **ConvertMapKeysToIsoAlpha2** | List<string> |  |
| **GetIsoAlpha2FromName** | string |  |
| **GetIsoAlpha3FromName** | string |  |
| **GetMapIdents** | List<string> |  |
| **GetMapKeyFromName** | string |  |
| **GetMapKeysFromNames** | List<string> |  |
| **GetNameFromIsoAlpha2** | string |  |
| **GetNameFromIsoAlpha3** | string |  |
| **NormalizeName** | string |  |
| **Simplify** `static` | string |  |

---

### Method Details

#### ConvertMapKeysToIsoAlpha2

**ConvertMapKeysToIsoAlpha2**(**mapKeys**: List<string>, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): List<string>

**Parameters**

- **mapKeys** (List<string>)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** List<string>


---

#### GetIsoAlpha2FromName

**GetIsoAlpha2FromName**(**name**: string, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): string

**Parameters**

- **name** (string)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** string


---

#### GetIsoAlpha3FromName

**GetIsoAlpha3FromName**(**name**: string, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): string

**Parameters**

- **name** (string)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** string


---

#### GetMapIdents

**GetMapIdents**(**key**: string): List<string>

**Parameters**

- **key** (string)  

**Returns** List<string>


---

#### GetMapKeyFromName

**GetMapKeyFromName**(**name**: string, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): string

**Parameters**

- **name** (string)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** string


---

#### GetMapKeysFromNames

**GetMapKeysFromNames**(**values**: List<object>, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): List<string>

**Parameters**

- **values** (List<object>)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** List<string>


---

#### GetNameFromIsoAlpha2

**GetNameFromIsoAlpha2**(**alpha2**: string, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): string

**Parameters**

- **alpha2** (string)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** string


---

#### GetNameFromIsoAlpha3

**GetNameFromIsoAlpha3**(**alpha3**: string, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): string

**Parameters**

- **alpha3** (string)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** string


---

#### NormalizeName

**NormalizeName**(**name**: string, **mapId**: string, **lang**: string, **report**: [IStiReport](../../Stimulsoft_Base/root/IStiReport.md)): string

**Parameters**

- **name** (string)  
- **mapId** (string)  
- **lang** (string)  
- **report** ([IStiReport](../../Stimulsoft_Base/root/IStiReport.md))  

**Returns** string


---

#### Simplify `static`

**Simplify**(**key**: string): string

**Parameters**

- **key** (string)  

**Returns** string

